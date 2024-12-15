Cytoarchitecture is a basic principle of microstructural brain parcellation. We introduce Julich-Brain, a
three-dimensional atlas containing cytoarchitectonic maps of cortical areas and subcortical nuclei.
The atlas is probabilistic, which enables it to account for variations between individual brains.
Building such an atlas was highly data- and labor-intensive and required the development of nested,
interdependent workflows for detecting borders between brain areas, data processing, provenance
tracking, and flexible execution of processing chains to handle large amounts of data at different spatial
scales. Full cortical coverage was achieved by the inclusion of gap maps to complement cortical maps.
The atlas is dynamic and will be adapted as mapping progresses; it is openly available to support
neuroimaging studies as well as modeling and simulation; and it is interoperable, enabling connection to
other atlases and resources.

aps of the microstructural segregation We created the Julich-Brain atlas in our labs
of the human brain can offer improved in Jülich and Düsseldorf (Fig. 1). It is a cytounderstanding of the biological sub- architectonic atlas containing probabilistic
strates of brain functions, dysfunctions, maps of cortical areas and subcortical nuclei.
and behavior. Cytoarchitecture—the Having started this endeavor in the mid-1990s,
arrangement of cells, their distribution, com-M we more recently resorted to “crowdsourcing”
position, and layering—is a major principle of strategies (but on a high professional level and
microstructural brain organization. It is closely based on profound expertise), which in turn
linked to the connectivity pattern of a region required Big Data–capable processing workand its function (1). Furthermore, cytoarchitec- flows. All of the necessary steps—preparation
ture allows multiple aspects of brain organi- of human brain tissue, microstructural mapzation (such as myeloarchitecture, molecular ping, analysis, and complex data processing—
architecture, gene expression, and activation are data-, time-, and labor-intensive, all the more
or resting-state networks) to be referenced to a so with increasing sample sizes and higher
common ground that serves as the interface to spatial resolution. It is thus impossible to prorepresent and integrate the different aspects vide whole-brain maps with sufficient deof brain organization (2). It is widely accepted tail by single researchers or small teams in
that a multifaceted but integrated approach is an acceptable time frame. Increased coma prerequisite for research into brain organi- puting power and storage capacities, as well
zation (3, 4). as improved algorithms and workflows for
Brodmann’s cytoarchitectonic map from data processing, now enable much faster
1909 was one of the first maps of its kind and and more robust processing at high spatial
is still widely used. It has several limitations; resolution.
for example, it shows only the left hemisphere However, not all datasets and analyses benof a single brain and therefore cannot account efit equally from improved data acquisition
for intersubject variability. Evidence has been techniques. Our cytoarchitectonic mapping
obtained that the number of cortical areas is efforts started more than 25 years ago. The
in the range of 180 or more (2, 5, 6), as com- brains have already been histologically propared to 43 areas in Brodmann’s map. Sub- cessed, and neither new high-field magnetic
cortical structures have been mapped with resonance imaging (MRI) data nor highthe same level of detail (7) but are not part of resolution blockface images can be acquired
the Brodmann atlas. Without analyzing and afterward. The quality of MRI data is thus
processing thousands of histological sections constrained by the quality available at the time
per brain with consistently high quality, the of acquisition. This may sometimes restrict the
variable cytoarchitecture of areas and nuclei in use of modern imaging tools and techniques,
a cytoarchitectonic map cannot be captured because these are often geared toward curwith sufficient spatial resolution (8). rently available data quality. Specific data

processing strategies considering both recent

1Institute of Neuroscience and Medicine (INM-1), Research and older datasets are mandatory. To ensure
Centre Jülich, Jülich, Germany. [2]C. and O. Vogt Institute for accuracy, reproducibility, and consistency of
Brain Research, University Hospital Düsseldorf, Heinrich data and processing steps over the entire data
Heine University Düsseldorf, Düsseldorf, Germany. life cycle, automated and reproducible work*Corresponding author. Email: k.amunts@fz-juelich.de (K.A.);
h.mohlberg@fz-juelich.de (H.M.) flows governed by provenance tracking are


We therefore developed a modular, flexible,
and adaptive framework to create probabilistic cytoarchitectonic maps, resulting from the
analysis of 10 postmortem human brains, for
each area (Fig. 2). Maps were aligned to two
widely used stereotaxic spaces, MNI-Colin27
and ICBM152casym space (9), and superimposed. The Julich-Brain atlas allows comparison of functional activations, networks,
genetic expression patterns, anatomical structures, and other data obtained across different
studies in a common stereotaxic reference
space (Fig. 3). The framework relies on longstanding expertise for handling whole human postmortem brains, cytoarchitectonic
mapping of a variety of cortical and subcortical regions, and computational expertise
to develop robust and adaptive tools, using
both local clusters and supercomputers. All
of these aspects have changed over time,
and the creation of a uniform, reproducible,
and probabilistic brain atlas depends on their
convergence.
The Julich-Brain atlas is based on histological sections of 23 postmortem brains (11 female,
12 male; mean age = 64 years, age range = 30 to
86 years; mean postmortem delay = 12 hours;
table S1) acquired from the body donor programs of the Anatomical Institute of the University of Düsseldorf. The brains were fixed
in formalin or Bodian solution, subjected to
MRI, embedded in paraffin, and serially cut
with a microtome into 20-mm sections (10).
Cell bodies were stained using a modified
Merker method. Histological sections were
digitized with flatbed scanners at 10 mm, reduced to an isotropic resolution of 20 mm,
framed to a fixed picture size, and stored
as lossless compressed gray-level images.
Two brains constitute complete series [the
“BigBrain datasets,” one of which was published in (11)], where every single section was
stained and digitized. The other brains were
stained with intervals of up to 15 sections. This
resulted in more than 24,000 histological sections. Histological processing and staining, including mounting of sections and removal of
small wrinkles and folds, entailed some degree
of local deformation, damage, or staining inhomogeneity. Although this was unavoidable,
fewer than 1% of the sections showed irretrievable damage (e.g., loss of substantial
parts of the tissue), and 20 to 30% had
small, local damages. To correct for distortions
in histological sections, we used the corresponding MRI datasets for 3D reconstruction
(Fig. 2). Rather severe areas of damage in
images of histological sections were manually and, where applicable, semiautomatically
corrected (11) (fig. S1A).
The time-consuming repairs and the considerable amount of computing time for processing the BigBrain datasets required a workflow


1Institute of Neuroscience and Medicine (INM-1), Research


-----

datasets, in combination with the complexity and diversity of the overall reconstruction
workflow, required time- and resource-effective
computational processing. This in turn required advanced management of big datasets,
computing, and provenance tracking (fig. S1).
On the basis of the reconstruction of BigBrain
1 (11), an adapted workflow was developed
for the reconstruction of BigBrain 2, which
includes an elaborate data provenance tracking system. It served as the basis for a generalpurpose dataflow management system that
allowed restricting the recalculation to only
those images that were affected by subsequent repairs (fig. S1A), resulting in a substantial reduction of computing time (12). In
addition, the pipeline of the BigBrain 2 dataset was closely linked to the overall workflow and was used in a similar way as for
the other 21 postmortem brains. To recover
the original shape and topology of the brain
volume, we computed a 3D reconstruction
of histological sections (fig. S3); for a recent
survey of methods, see (13). The approach is
based on a multistep procedure starting
from an initially 3D dataset at a resolution
of 0.3 mm[3] and is explained in the supplementary materials.
Human brains show a variable pattern of
sulci and gyri, plus intersubject variability in
shape, localization, and extent of cytoarchitectonic regions (2). To make brains comparable, we initially transferred 3D reconstructed
histological datasets to the stereotaxic space
of the single-subject MNI-Colin27 template
(fig. S3). In contrast to templates resulting
from an “average” of many brain datasets [e.g.,
the MNI305 template (9)], the individual reference brain shows a detailed (but not representative) anatomy, thus allowing a precise
registration of the gross anatomy of the postmortem brains to that space. Because mean
group datasets are well accepted in the neuroimaging community, nonlinear transformations
into the ICBM2009casym space were also
computed. This template represents a compromise between the detailed but specific
anatomy of the MNI-Colin27 brain and the
more generic but smoother MNI305 template.
The representation of the maps in these two
spaces makes Julich-Brain interoperable with
other atlases and resources [e.g., (6, 7, 14, 15)]
and connects it to large cohort studies such
as the Human Connectome Project (HCP;
[www.humanconnectome.org) and UK Biobank](http://www.humanconnectome.org)
[(www.ukbiobank.ac.uk) (see also supplementary](http://www.ukbiobank.ac.uk)
materials).
Different approaches are available to register postmortem brains to each other [for
an overview, see (13)]. To develop an atlas
with both cortical areas and subcortical nuclei, we started with a volume-based approach,
which provided a consistent registration


tical structures. An elastic 3D registration
was applied with a well-matched parameter
set that was also used for the 2D registrations. The method showed high reliability
in both postmortem and in vivo datasets. The
registration of all postmortem brains to the
MNI-Colin27 and the ICBM152casym reference brains resulted in a similar folding
pattern and shape of the 3D-reconstructed
datasets and the template (fig. S3). The 3D
vector field transformations of each 3Dreconstructed histological dataset were stored
and were later applied to the mapped cytoarchitectonic areas.
To date, 41 projects have resulted in maps of
248 cytoarchitectonic areas (Fig. 1). Projects
were carried out by doctoral students, researchers, and guest scientists and have been published in peer-reviewed scientific journals [for
an overview, see (2)]. These publications provide details of cytoarchitecture, localization
with respect to sulci/gyri and stereotaxic space,
intersubject variability, and other features;
some of them also refer to the relationship of
the areas to functional imaging studies, receptor architecture, and/or area-specific gene
expression.


Each map is based on analyses of 10 postmortem brains (5 male, 5 female), which were
selected from the pool of 23 brains on the basis
of their folding pattern, the presence of already
mapped neighboring areas, the orientation
of the cutting plane, etc. Consequently, overlapping and sometimes similar samples were
analyzed for different regions.
Depending on the size and shape of a structure, every 15th to 60th section was mapped
over the whole extent of a cytoarchitectonic
region. Borders between cortical areas were
identified using image analysis and statistical
criteria to make mapping reproducible (16).
The positions of borders were labeled in the
digitized sections, and a closed polygon (contour line) marked its extent in the section
(fig. S4). For subcortical nuclei, the outer boundaries of nuclei were identified in histological
sections and labeled as closed polygonal lines.
Contour lines were also used for a quality
check of each map over its full extent (fig. S4).
As a next step, individual shrinkage-corrected
volumes for each area/nucleus, hemisphere,
and brain were calculated (see supplementary materials). The analysis of the 120 currently available areas showed considerable

|expression.|Col2|
|---|---|
|||
|||


Fig. 1. Cytoarchitectonic maximum probability maps of Julich-Brain in MNI-Colin27 reference space.
Areas have different colors; views of the left and right hemispheres are shown. The lower panel
shows structures located in the depths of the brain. Datasets of published areas are freely available
through the Julich-Brain and HBP data portals. Both web-based interfaces allow the visualization
and inspection of probabilistic and maximum probability maps as surface (pial, smoothed white matter,


Fig. 1. Cytoarchitectonic maximum probability maps of Julich-Brain in MNI-Colin27 reference space.

shows structures located in the depths of the brain. Datasets of published areas are freely available

and inspection of probabilistic and maximum probability maps as surface (pial, smoothed white matter,


-----

intersubject differences in volume (fig. S5),
but differences between the two hemispheres
were not significant at a global level, nor
were differences between male and female
brains (see table S2 for full information on these
volumes). The list of volumes is a growing
resource together with the probabilistic maps
of areas and nuclei, made available and constantly updated through the Knowledge graph
of the European Human Brain Project (HBP;
[see https://ebrains.eu).](https://ebrains.eu)


The comparison of the degree of intersubject variability suggests differences between
brain regions (fig. S5). For example, we found
high variability (i.e., low values for probability)
in Broca’s region with areas 44 and 45 and the
superior parietal lobule, whereas the occipital
pole with the primary and secondary visual
cortices (BA17/18) and area Te3 in the temporal lobe appeared less variable.
Previous and ongoing mapping projects
resulted in more than 10,616 XML files con

taining 85,210 contour lines with 3,737,771 points
and a total length of 1961 m. Stacks with contour lines were managed using the open-source
version control software Subversion, which
automatically manages files and directories
so as to document the complete history of how
the localization of an areal border might have
changed over its life cycle (fig. S1B). Changes
may occur when a new mapping project requires reanalysis of an already existing map,
but these have been small in the past.

|of the European Human Brain Project (HBP; see https://ebrains.eu).|;|Previous and ong resulted in more tha|
|---|---|---|
||||
||||
||||

|and secondary visual rea Te3 in the tempo- riable. ng mapping projects 0,616 XML files con-|Col2|Col3|the localization of an areal border might have changed over its life cycle (fig. S1B). Changes may occur when a new mapping project re- quires reanalysis of an already existing map, but these have been small in the past.|
|---|---|---|---|
|||||
|||||


Fig. 2. Workflow of the 3D reconstruction of serial histological sections
and alignment of brain data to a reference space, cytoarchitectonic analysis
in 2D images, and the computing of the probabilistic Julich-Brain atlas.
(A) To recover the 3D shape of a postmortem brain, we applied a combination of
linear and nonlinear processing steps at different scales based on the undistorted
MRI dataset, and optional on blockface images, obtained during sectioning. The
digitized histological images were repaired and corrected for illumination and
optical imbalances. A rigid section-to-section alignment was computed to create
a first approximate 3D reconstruction. It served to align the MRI dataset to
the corresponding section planes by a rigid-body transformation. The sections
were nonlinearly registered to the sections of the MRI by an elastic method.


by section, to a median filtered version. (B) The cytoarchitecture was analyzed in
consecutive histological sections covering the complete extent of an area and
characterized by the gray-level index (16). Contour lines of the areas were
submitted to a data repository, 3D-reconstructed, and topologically normalized.
Linear and nonlinear transformations were applied to the areas, and areas
were superimposed to form the cytoarchitectonic probability map. (C) Volumeand surface-based maximum probability maps of the Julich-Brain atlas were
computed. To effectively organize the intensive computations, we implemented a
data processing management system that allowed distributed processing of a
large number of datasets across multiple CPU cores. It was designed to scale up
well from a single core computer system up to thousands of computing nodes in


-----

The areas and nuclei were also transformed to
thestereotaxic MNI-Colin27 and ICBM2009casym
reference space, using the computed whole-brain
transformations, and superimposed (see supplementary materials). The resulting probabilistic, cytoarchitectonic maps were stored as
volume data files. By projecting the probability
values onto the surface, a surface-based representation of cytoarchitectonic cortical maps
was computed (Fig. 1 and fig. S6). The result

ing values, indicating the probability of an area
or nucleus being localized in a given voxel (0%
to 100% overlap), range from 0.0 to 1.0; this
number provides a measure for variations of a
given area in localization and extent from brain
to brain (i.e., intersubject variability). These
probabilistic maps overlap with each other;
that is, voxels in reference space can usually be
assigned to more than one area, each with a
well-defined probability, summing up to 100%


(fig. S6). We found that about 50% of the voxels
were associated with a single area or nucleus,
35% with two, and 15% with three or more.
To reduce complexity and to visualize the extent of areas comparable to Brodmann’s map,
we calculated a maximum probability map
(MPM). Each voxel in the reference brain was
assigned to the cytoarchitectonic area with
the highest probability at that position (17).
The average overlap fraction of all currently

|listic, cytoarchitectonic maps were stored as volume data files. By projecting the probability values onto the surface, a surface-based repre- sentation of cytoarchitectonic cortical maps was computed (Fig. 1 and fig. S6). The result-|Col2|
|---|---|
|||
|||

|ct variability). These lap with each other; e space can usually be ne area, each with a summing up to 100%|Col2|we calculated a maximum probability map (MPM). Each voxel in the reference brain was assigned to the cytoarchitectonic area with the highest probability at that position (17). The average overlap fraction of all currently|
|---|---|---|
||||
||||
||||


Fig. 3. Examples of applications of the Julich-Brain atlas. (A) Screenshot
of the web-based atlas tool in the Human Brain Atlas of the HBP showing probability
maps in different views. (B and C) JuGEx enables analysis of differential gene


connectivity (e.g., left Broca’s area 45) (C). (D) Superposition of the probabilistic map
of Broca’s area 44 on a dataset of a patient with a brain lesion and aphasia. The maps
allow precise statements about the microanatomical location of a neuroimaging


’


-----

mapped and adjacent areas results in a threshold value of about 35%. Under the assumption
that this threshold also applies to MPM borders
to yet unmapped areas, this threshold is used
to cut the MPM toward unmapped regions.
The visualization of neighboring areas demonstrates that gyri may be occupied by one
or more areas that differ in cytoarchitecture
and function. Conversely, single areas may be
found on more than one gyrus; examples are
given for the auditory cortex in fig. S7. The
manifold of relationships between areas and
sulci/gyri illustrates the advantage and higher
precision of cytoarchitectonic probabilistic maps
as compared to macroscopic brain maps.
At present, about 70% of the cortical surface
has been covered by completed and published
mapping projects. However, there are still
areas that have not been mapped and represent projects for future research. To provide
whole-brain coverage for the cortex (fig. S8),
we have combined parts of the cortex that have
not yet been charted into several “gap maps,”
pooling these uncharted areas in a given brain
region (see supplementary materials and fig.
S9). The distributions were modeled so that
probabilistic gap maps were computed in analogy to the other maps. As mapping progresses,
new maps are continuously replacing gap maps
while the process is captured and documented
by provenance tracking. Consequently, the atlas
is not static (as is, e.g., Brodmann’s map) but
rather represents a “living map”—a concept
that is known, for example, from geography for
navigating complex spaces.
Gap maps allow computation of a parcellation covering the entire cortical surface and
the unambiguous assignment of each position
to a cortical region. Together with the increasing number of probabilistic maps of subcortical
nuclei, gap maps contribute to a whole-brain
human atlas. Maps in Julich-Brain can be combined with findings in other atlases and maps;
one example involves the study of microstructural correlates of activations from neuroimaging studies of healthy subjects and patients
(Fig. 3). Moreover, Julich-Brain contributes
to brain modeling and simulation through
informing the model by a functionally sound
microstructural parcellation. It is expected
that this will open new avenues to generate
models of brain activity such as those used in
the treatment of epilepsy, where personalized
brain models are used to predict the propagation of seizures (18).


The modular, flexible, and extensible workflows cover a broad range of steps from image
acquisition to 3D reconstruction and the generation of probabilistic maps, which can be
found in several areas of research. The methodical framework (or parts of it) can be extended to brains of other species, and it can be
used to process section images labeled by other
techniques (e.g., immunohistology). New modules can be added to the workflows for applications such as mapping brain areas on the
basis of deep learning (19).
The Julich-Brain atlas is a freely available re[source (www.julich-brain.org). Maps have been](http://www.julich-brain.org)
made available through differenttools and web[sites such as the SPM anatomy toolbox (www.fz-](http://www.fz-juelich.de/inm/inm-7/JuelichAnatomyToolbox)
[juelich.de/inm/inm-7/JuelichAnatomyToolbox),](http://www.fz-juelich.de/inm/inm-7/JuelichAnatomyToolbox)
[FSL(https://fsl.fmrib.ox.ac.uk), FreeSurfer (https://](https://fsl.fmrib.ox.ac.uk)
[surfer.nmr.mgh.harvard.edu), and the EBRAINS](https://surfer.nmr.mgh.harvard.edu)
[research infrastructure of the HBP (https://](https://ebrains.eu/services/atlases)
[ebrains.eu/services/atlases). The maps can be](https://ebrains.eu/services/atlases)
linked to diffusion tensor imaging (DTI)–based
connectivity data (Fig. 3C) and to gene expression data provided by the Allen Institute for
[Brain Science (https://alleninstitute.org/what-](https://alleninstitute.org/what-we-do/brain-science)
[we-do/brain-science) through the JuGEx tool](https://alleninstitute.org/what-we-do/brain-science)
(20) to enable a multimodal perspective on human brain organization (Fig. 3B).
Julich-Brain represents a new kind of human
brain atlas that is (i) cytoarchitectonic to reflect
a basic principle of the brain’s microstructural
parcellation; (ii) whole-brain,to cover both the
cerebral cortex and subcortical nuclei; (iii)
3D-probabilistic, to consider variations between individual brains in stereotaxic space;
(iv) dynamic, a living atlas, to be supplemented
by maps of new areas or subdivision of existing
maps of areas (e.g., when new studies suggest
a finer or new parcellation); (v) flexible, to
allow for modifications of modules in the
workflows for other data modalities, organs,
or species; (vi) open-access and based on FAIR
principles, to contribute to studies by other
researchers addressing structure-function relationships and network organization; and (vi)
interoperable, to link it to other atlases and
resources that provide complementary information about brain organization.

REFERENCES AND NOTES


[science.sciencemag.org/content/369/6506/988/suppl/DC1](https://science.sciencemag.org/content/369/6506/988/suppl/DC1)
Materials and Methods
Figs. S1 to S9
Tables S1 and S2
References (21–56)

27 February 2020; accepted 24 June 2020
Published online 30 July 2020
10.1126/science.abb4588


5. R. Nieuwenhuys, C. A. J. Broere, Brain Struct. Funct. 222,
465–480 (2016).
6. M. F. Glasser et al., Nature 536, 171–178 (2016).
7. J. K. Mai et al., Atlasof the HumanBrain (Academic Press, ed. 4, 2015).
8. K. Zilles, K. Amunts, Nat. Rev. Neurosci. 11, 139–145 (2010).
9. A. C. Evans, A. L. Janke, D. L. Collins, S. Baillet, Neuroimage 62,
911–922 (2012).
10. K. Amunts et al., J. Neurosci. 27, 1356–1364 (2007).
11. K. Amunts et al., Science 340, 1472–1475 (2013).
12. H. Mohlberg et al., in Brain-Inspired Computing: Second
International Workshop, BrainComp 2015, K. Amunts et al., Eds.
(Springer, 2016), pp. 15–27.
13. J. Pichat, J. E. Iglesias, T. Yousry, S. Ourselin, M. Modat,
Med. Image Anal. 46, 73–105 (2018).
14. H. Damasio, Human Brain Anatomy in Computerized Images
(Oxford Univ. Press, ed. 2, 2005).
15. S. L. Ding et al., J. Comp. Neurol. 524, 3127–3481 (2016).
16. A. Schleicher et al., Anat. Embryol. 210, 373–386 (2005).
17. S. B. Eickhoff et al., Neuroimage 25, 1325–1335 (2005).
18. T. Proix, F. Bartolomei, M. Guye, V. K. Jirsa, Brain 140, 641–654 (2017).
19. H. Spitzer et al., in Medical Image Computing and Computer
Assisted Intervention—MICCAI 2018, Part III, A. F. Frangi et al.,
Eds. (Springer, 2018), pp. 663–671.
20. S. Bludau et al., Brain Struct. Funct. 223, 2335–2342 (2018).

ACKNOWLEDGMENTS


We thank more than 41 postdocs, doctoral students, guests,
and colleagues who contributed to the mapping of 248
cytoarchitectonic areas and nuclei; the technical assistants of the
C. and O. Vogt Institute of Heinrich Heine University Düsseldorf
and Research Centre Jülich; S. Eickhoff, R. Hübbers, P. Pieperhoff,
N. Palomero-Gallagher, S. Caspers, T. Dickscheid, and A. C. Evans
for intensive discussions; A. Schleicher for developing the original
observer-independent mapping approach; our partners of the
International Consortium for Human Brain Mapping who stimulated
and actively supported this research; and our colleagues at the Jülich
Supercomputing Centre, in particular B. Tweddell and T. Lippert.
Funding: Supported by the Portfolio Theme “Supercomputing and
Modeling for the Human Brain” of the Helmholtz Association, the
European Union Seventh Framework Programme (FP7/2007-2013,
HBP), and the European Union’s Horizon 2020 Research and
Innovation Programme, grant agreements 604102 (HBP SGA1),
785907 (HBP SGA2), and 945539 (HBP SGA3). Author
contributions: K.A. and K.Z. developed the concept of 3D
probabilistic cytoarchitectonic brain mapping and atlas. K.A. is
overseeing the atlas projects, contributed to methodological
developments, and drafted the manuscript. H.M. developed and
adapted the methodology and the software for data processing
and atlas building, and drafted the manuscript. S.B. developed new
tools for analysis and mapping of cytoarchitectonic areas. All authors
contributed to the writing of the manuscript. Competing interests:
The authors declare no competing interests. Data and materials
availability: All data are available in the main text or the
supplementary materials. Various data modalities of the already
published maps of brain areas and the complete atlas are available
[online at www.julich-brain.org and via EBRAINS (https://ebrains.eu/)](http://www.julich-brain.org)
(DOI: 10.25493/TAKY-64D). Previously developed parts of the
workflows were published earlier; new scripts for computing the
Julich-Brain Atlas and for analyzing contour lines and gap maps
[(https://doi.org/10.5281/zenodo.3906413) are provided via the git](https://doi.org/10.5281/zenodo.3906413)
[repository, https://github.com/JulichBrainAtlas.](https://github.com/JulichBrainAtlas)

SUPPLEMENTARY MATERIALS


1. A. Goulas, K. Zilles, C. C. Hilgetag, Trends Neurosci. 41,
775–788 (2018).
2. K. Amunts, K. Zilles, Neuron 88, 1086–1107 (2015).
3. D. C. Van Essen et al., Proc. Natl. Acad. Sci. U.S.A. 116,
26173–26180 (2019).
4. B. Fischl, M. I. Sereno, Neuroimage 182, 219–231 (2018).


-----

