# Apptainer

This document explains how to use the apptainer container runtime on a JSC supercomputing system like JURECA-DC or JUWELS Booster. The presented examples are one way to use container and are intended to get you started with using the software.

**Disclaimer**: These are examples to show you the principles, they are not necessarily meant to be followed blindly. If you encounter errors (e.g., files are named differently, permission errors), please check if you used the right files.

## Getting access

First, follow the instructions here to enable your account for apptainer.

## Preparing your environment

Apptainer images and its cache can take a lot of space, so it is not a good idea to store them in your HOME directory. To avoid quota issues, it is strongly suggested to move the ~/.apptainer folder to a larger storage, like PROJECT.

Example:
```bash
# activate your project (here, cjinm16 as example)
jutil env activate -p cjinm16

# be careful with this!
# rm -rf ~/.apptainer

# create symlink (adapt target directory if needed)
ln -sr ~/.apptainer ${PROJECT}/${USER}/.apptainer
```

## Pull an image

Apptainer can build native apptainer images, but this will not be addressed here. We will instead pull a pre-built docker image from an existing registry like dockerhub. If you want, you can use gitlab-ci or a similar CI framework to build your own containers, push them to a registry, and pull those with apptainer.

In this example, we will use the default PyTorch container provided by NVidia.

```bash
# Go somewhere with enough space
mkdir -p ${PROJECT}/${USER}/tmp
cd ${PROJECT}/${USER}/tmp

# Pull from https://catalog.ngc.nvidia.com/orgs/nvidia/containers/pytorch
IMAGE_NAME=container_pytorch_24_11.sif
apptainer pull ${IMAGE_NAME} docker://nvcr.io/nvidia/pytorch:24.11-py3
```

This can take a bit, so go grab a coffee. The container will be stored in the *.sif file we specified.

## Using the container

There are multiple ways to use the container.

### Interactive shell

We can start a shell inside the container:
```bash
apptainer shell ${IMAGE_NAME}
```

### Running a command

We can execute a single command inside the container:
```bash
apptainer exec ${IMAGE_NAME} python3 -c "print('Hello world')"
```

## Accessing files

Different from docker, apptainer will have access to the entire file system of the host system. If there are collisions, or something does not work as expected, you can specify additional folders to bind into the container using the -B option.

```bash
# Mount /p of the JSC file systems into the container
apptainer exec -B /p ${IMAGE_NAME} python3 -c "print('Hello world')"

# Mount a specific library from the host into the container (advanced, only use if you know what you are doing)
apptainer exec -B /usr/lib64/libcrypto.so.3 ${IMAGE_NAME} python3 -c "print('Hello world')"
```

## Using GPUs

If you want to use GPUs, you should specify the --nv flag:
```bash
apptainer exec --nv ${IMAGE_NAME} python3 -c "import torch; print(torch.cuda.is_available())"
```

## Using MPI

Using apptainer with MPI is possible, but the right environment variables have to be set:
```bash
export SLURM_MPI_TYPE=pspmix
export PMIX_SECURITY_MODE=native
srun -n 1 apptainer exec --nv ${IMAGE_NAME} python3 -c "import torch; print(torch.cuda.is_available())"
```

## Python environment

It is possible to easily extend a container by creating a python environment. Here, the most important thing is to ensure that the creation and modification of the environment is only done from the container, not the system python. Here are some scripts that you can use to create, modify, and create the environment.

```bash
# file: create_venv.sh
python3 -m venv my_venv

# create the environment
apptainer exec ${IMAGE_NAME} bash create_venv.sh

# file: execute_with_venv.sh
# Can be used to execute any command within the virtual enviroment
source my_venv/bin/activate
$@

# example: install something with pip
apptainer exec --nv bash execute_with_venv.sh pip install matplotlib

# example: run a script
apptainer exec --nv bash execute_with_venv.sh python my_script.py
```