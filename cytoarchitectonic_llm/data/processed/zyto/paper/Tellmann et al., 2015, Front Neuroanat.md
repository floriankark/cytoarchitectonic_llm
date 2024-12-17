_Edited by:_
_Kathleen S. Rockland,_
_Boston University School of Medicine,_
_USA_

_Reviewed by:_
_Antonio Di Ieva,_
_Macquarie University Hospital,_
_Australia_
_Andreas Wree,_
_University of Rostock, Germany_

_*Correspondence:_
_Katrin Amunts and Stefanie Tellmann,_
_Institute of Neuroscience and_
_Medicine (INM-1), Structural and_
_Functional Organization of the Human_
_Brain, Research Centre Jülich,_
_Leo-Brandt-Straße, D-52428 Jülich,_
_Germany_
_k.amunts@fz-juelich.de;_
_s.tellmann@fz-juelich.de_

_Received: 12 March 2015_
_Accepted: 19 April 2015_
_Published: 13 May 2015_

_Citation:_
_Tellmann S, Bludau S, Eickhoff S,_
_Mohlberg H, Minnerop M_
_and Amunts K (2015)_
_Cytoarchitectonic mapping of the_
_human brain cerebellar nuclei_
_in stereotaxic space and delineation_
_of their co-activation patterns._
_Front. Neuroanat. 9:54._
_[doi: 10.3389/fnana.2015.00054](http://dx.doi.org/10.3389/fnana.2015.00054)_


p y
[doi: 10.3389/fnana.2015.00054](http://dx.doi.org/10.3389/fnana.2015.00054)

# Cytoarchitectonic mapping of the human brain cerebellar nuclei in stereotaxic space and delineation of their co-activation patterns

_[Stefanie Tellmann[1,2]*, Sebastian Bludau[2], Simon Eickhoff[2,3], Hartmut Mohlberg[2],](http://community.frontiersin.org/people/u/172422)_
_[Martina Minnerop[2]](http://community.frontiersin.org/people/u/103410)_ _[and Katrin Amunts[2,4]*](http://community.frontiersin.org/people/u/6448)_

_1 Department of Psychiatry, Psychotherapy and Psychosomatics, RWTH Aachen University and JARA-Brain, Aachen,_
_Germany,_ _[2]_ _Institute of Neuroscience and Medicine (INM-1), Structural and Functional Organization of the Human Brain,_
_Research Centre Jülich, Jülich, Germany,_ _[3]_ _Institute for Clinical Neuroscience and Medical Psychology, Heinrich Heine_
_University, Düsseldorf, Germany,_ _[4]_ _Cécile and Oskar Vogt Institute of Brain Research, Heinrich Heine University, Düsseldorf,_
_Germany_

The cerebellar nuclei are involved in several brain functions, including the modulation of
motor and cognitive performance. To differentiate their participation in these functions,
and to analyze their changes in neurodegenerative and other diseases as revealed
by neuroimaging, stereotaxic maps are necessary. These maps reflect the complex
spatial structure of cerebellar nuclei with adequate spatial resolution and detail. Here
we report on the cytoarchitecture of the dentate, interposed (emboliform and globose)
and fastigial nuclei, and introduce 3D probability maps in stereotaxic MNI-Colin27
space as a prerequisite for subsequent meta-analysis of their functional involvement.
Histological sections of 10 human post mortem brains were therefore examined.
Differences in cell density were measured and used to distinguish a dorsal from a
ventral part of the dentate nucleus. Probabilistic maps were calculated, which indicate
the position and extent of the nuclei in 3D-space, while considering their intersubject
variability. The maps of the interposed and the dentate nuclei differed with respect to
their interaction patterns and functions based on meta-analytic connectivity modeling
and quantitative functional decoding, respectively. For the dentate nucleus, significant
(p < 0.05) co-activations were observed with thalamus, supplementary motor area
(SMA), putamen, BA 44 of Broca’s region, areas of superior and inferior parietal cortex,
and the superior frontal gyrus (SFG). In contrast, the interposed nucleus showed
more limited co-activations with SMA, area 44, putamen, and SFG. Thus, the new
stereotaxic maps contribute to analyze structure and function of the cerebellum. These
maps can be used for anatomically reliable and precise identification of degenerative
alteration in MRI-data of patients who suffer from various cerebellar diseases.

Keywords: cytoarchitecture, cerebellar nuclei, brain mapping, human brain atlas, SPM Anatomy Toolbox

## Introduction

The cerebellar nuclei show a complex morphology and their full extent is partly invisible
in routine Magnetic Resonance Imaging (MRI). Recently, a MRI-based atlas (SUIT) of the


-----

three parted cerebellar nuclei (dentate, interposed, and fastigial),
which is based on 7T MR images of 23 subjects, has been introduced (Diedrichsen et al., 2011). Its spatial resolution is 0.5 mm.
This resolution, however, does not enable to identify cellular
details as obtained in histological mapping in cell-body stained
sections. Such detailed maps could be beneficial for an anatomical reliable and precise identification of activation foci obtained
in neuroimaging experiment, or degenerative alteration in MRIdata of patients who suffer from various cerebellar diseases.
Impairment of the cerebellum and its output pathways can
lead to several clinical syndromes, e.g., cerebellar ataxia (Manto,
2002). Neurodegeneration, targeting within the cerebellum especially the dentate nucleus, occurs, e.g., in an autosomal dominant
inherited disorder, called Spinocerebellar Ataxia Type 3 (SCA3;
Rub et al., 2008, 2013; Scherzed et al., 2012). However, these neuropathologically observed changes of the dentate nuclei in SCA3
have yet not been demonstrated by imaging techniques in vivo,
most probably due to the spatial resolution.
The four cerebellar nuclei, i.e., the dentate (DN), emboliform
(EN), globose (GN), and fastigial nucleus (FN), are located in the
depth of the cerebellar hemispheres in close vicinity to the fourth
ventricle. The most laterally located dentate nucleus appears as
a convoluted band containing rounded large multipolar neurons. It is the largest nucleus and well visible in routine MR
images. A partition of the human dentate nucleus into a dorsal micro- and a ventral macrogyric part has been mentioned
in an early description of the cerebellar nuclei (Stilling, 1864).
Since then, this subdivision has been repeatedly replicated both in
early (Winkler, 1926; Vogt and Vogt, 1942; Hassler, 1950; Fix and
Treff, 1970) and more recent (Arras, 1987; Voogd, 2003; Deoni
and Catani, 2007) studies. It was also reported that the ventral
part contains more iron than the dorsal one (Gans, 1924), which
may indicate an increased vulnerability for degenerative disorders (e.g., Schulz and Pandolfo, 2013). A similar dorsal–ventral
subdivision of the dentate nucleus was also shown in primates by
using invasive tracing (Dum and Strick, 2003).
In contrast to the dentate nucleus, the interposed nucleus – the
wedge-shaped emboliform nucleus and the more rounded globose nucleus – are found within the paravermal region, next to
the medial border of the dentate nucleus, and close to the dentate
hilus. The fastigial nucleus, also known as tegmental nucleus, is
the most medially located cerebellar nucleus and builds the roof
of the fourth ventricle (e.g., Kozlova, 1984; Nieuwenhuys et al.,
2008). Each nucleus receives inhibitory afferents from distinct
parts of the ipsilateral cerebellar cortex. Large parts of the cerebellar cortex project to the dentate nuclei of both hemispheres.
The interposed nuclei receive information from the paravermal
zone, and the fastigial nucleus from the vermal cerebellar cortex
as well as from the flocculus (Manto, 2002).
All cerebellar nuclei are interconnected with the rest of the
brain through the cerebellar peduncles. The middle cerebellar
peduncle relays information from the cerebral cortex via the pontine nuclei to cerebellar structures. Efferent fibers of the dentate
and interposed nuclei reach, via the superior peduncle, thalamic nuclei, and sensorimotor areas (Carpenter, 1991; Manto,
2002; Dum and Strick, 2003). Further efferents from the dentate nucleus project to the red nucleus and subsequently to the


inferior olives; the latter in turn project back to the dentate
nucleus, forming the Guillain-Mollaret-Triangle (Lavezzi et al.,
2009). The fastigial nucleus sends projections through the inferior peduncle to the vestibular nuclei and the reticular formation.
A few fibers depart from the cerebellar uncinate fascicle and
ascend to thalamic subnuclei VLc and VPLo (Carpenter, 1991).
The vascular network forms another aspect of cerebellar organization. The cerebellar nuclei are supplied by the rhomboidal
artery, a branch of the superior cerebellar artery (Icardo et al.,
1982). It runs in parallel to the superior cerebellar peduncle.
When the hilum of the dentate nucleus is reached, the rhomboidal artery divides into a network of smaller vessels, the arcuate
arterioles, showing a precise vascular pattern, and building anastomoses with cortical branches from the posterior inferior cerebellar artery (Icardo et al., 1982). The veins of the dentate nucleus
are composed of several veins draining its external surface (into
the venous star and the cortex-perforating veins) and one single vein draining its internal surface, emerging from the hilum
of the dentate nucleus, and running along the superior cerebellar peduncle to the precentral cerebellar vein (Tschabitscher and
Perneczky, 1976; Tschabitscher, 1979; Di Ieva et al., 2011).
The role of mammalian cerebellar nuclei in motor functions
has been described in detail (Jansen and Brodal, 1942; Chambers
and Sprague, 1955; Jansen et al., 1958), but in accordance to
more recent studies the cerebellar nuclei – especially the dentate nucleus – are not only involved in modulation of movements
but also in cognition (Dum and Strick, 2003; Schmahmann and
Caplan, 2006; Schmahmann, 2010; Kuper et al., 2011a, 2012;
Timmann, 2012). The dorsal part of the dentate nucleus is supposed to be responsible for motor performance whereas a ventral
part was identified as cognitive or non-motor part. Assuming
a functional subdivision of the cerebellar nuclei (Manto, 2002;
Timmann et al., 2003), it was postulated that certain nuclei or
subdivisions of a nucleus are involved in a specific task of cognition and even emotion (see also Gerwig et al., 2003; Maschke
et al., 2003; McNaughton et al., 2004; Kuper et al., 2013). For
example it has been shown that the fastigial and interposed
nuclei take part in conditioning (Timmann, 2012). The dentate
nucleus, regarded as the phylogenetic highest developed cerebellar nucleus in humans (e.g., Mihajlovic and Zecevic, 1986;
O’Rahilly and Müller, 2006), seems to be involved in speech or
cognitive–associative learning (Thurling et al., 2011).
Several studies reported data regarding volumes, cell densities, and cell sizes of the cerebellar nuclei in humans (cf. Kölliker,
1889; Lugaro, 1895; Cajal and Santiago, 1953; Braak and Braak,
1983; Kozlova, 1984; Mihajlovic and Zecevic, 1986; Arras, 1987;
Yamaguchi et al., 1989; Carpenter, 1991; Voogd, 2003; O’Rahilly
and Müller, 2006; Manto, 2010; Ristanovic et al., 2010). Most of
these studies were confined to the dentate nucleus and did not
provide the nowadays required resolution and histologic preparation standards (e.g., shrinkage correction). The most accurate
histological post mortem data are based on 100 human cerebella
(age range 22–72 years) with a histological sections thickness
of 0.5 mm (Kozlova, 1984). Albeit only maxima of the x, y, z
extension had been reported this data allowed to roughly estimate the volume of each cerebellar nucleus. Diedrichsen et al.
(2011) provided MR-based volume data of the cerebellar nuclei


-----

and additionally computed the mean of the x, y, and z maxima, allowing an indirect comparison with Kozlova’s (1984) data.
The aim of the present study was to map the cerebellar nuclei in
histological sections of 10 post mortem brains to create cytoarchitectonic 3D probability maps in a standard reference space
and to evaluate anatomical and functional partition of the cerebellar nuclei. Therefore we integrated the computed maps in
the SPM Anatomy Toolbox (Eickhoff et al., 2005), and then
used the respective representations for meta-analytic connectivity modeling as well as functional decoding (Eickhoff et al., 2012).
Consequently we achieved a cytoarchitectonically based representation of the cerebellar nuclei in 3D space, and assigned its
corresponding function by meta-analytic connectivity modeling.

## Materials and Methods

Histological Techniques
We investigated 10 human post mortem brains (male/female: 5/5,
age 58.7 ± 17.3 years, range 30–85 years; cf. Table 1) collected
through the body donor program of the University of Düsseldorf
(Germany) in accordance to local legal and ethical requirements.
Subjects had no known history of neurological or psychiatric diseases. Details of the histological processing have been previously
described in detail (e.g., Amunts et al., 1999). In short, brains
were fixed for several months in 4% formalin or Bodian fixative.
During fixation, the brains were suspended on the basilar artery
to avoid compression or distortions. T1-weighted MRI scans

[1.5T Siemens Magnetom SP scanner, 3D fast low angle shot (3D
FLASH) pulse sequence, flip angle = 40[◦], TR = 40 ms, TE = 5 ms,
voxel size = 1 mm × 1 mm × 1.17 mm] were obtained to get
a shape reference for further 3D-reconstruction of the histological sections. Artifacts (e.g., shrinkage of the brain, embedding
in paraffin, and distortion of the sections due to cutting) could
be eliminated in the reconstructed volume by matching it with
the MR volume of the same brain using linear and non-linear
correction procedures (cf. Homke et al., 2009). Following dehydration and embedding in paraffin, the brains were sectioned

TABLE 1 | Sample of post mortem brains used for cytoarchitectonic
analysis.

ID Age Sex Shrinkage Brain Cause of death
factor weight (g)

5 59 Female 2.15 1142 Cardio-respiratory
insufficiency

6 54 Male 2.50 1757 Myocardial infarct

7 37 Male 2.25 1437 Heart failure

8 72 Female 1.90 1216 Renal failure

9 79 Female 1.51 1110 Heart failure

10 85 Female 1.72 1046 Mesenteric artery
infarction

11 74 Male 2.20 1381 Cardiac infarction

12 43 Female 2.14 1198 Cardio-respiratory
insufficiency

15 54 Male 1.60 1260 Accident

21 30 Male 1.84 1409 Morbus Hodgkin


(20 µm). Nine coronal and one horizontal series of sections
were analyzed. The sections were mounted on gelatin-coated
glass slides, and stained for cell bodies with a modified silver
method (Merker, 1983). On digital images of every 60th section
the region of interest was marked and captured using a light
microscope (Zeiss). The contours of the nuclei were drawn in
serial section of both hemispheres, using high-resolution images
(20 µm) of histological sections. Therefore, every 15th section
was scanned with a flatbed scanner. The identification of the
nuclei was done in accordance to criteria described in previous studies (e.g., Stilling, 1864; Weidenreich, 1899; Jakob, 1928;
Carpenter, 1991; Nieuwenhuys et al., 2008).

Volumetric Analysis of the Cerebellar Nuclei
The volumes of the nuclei were measured as previously described
(Amunts et al., 2007). They were normalized and expressed as the
fraction of the individual total brain volume in order to account
for individual differences in total brain volume. The volumes
were tested for sex and interhemispheric differences, as well as
their interaction using pairwise permutation tests (p < 0.05; false
discovery rate (FDR) corrected for multiple comparisons).

Analysis of the Subdivision of the Dentate
Nucleus
Cell densities of the dorsal and ventral parts of the dentate
nucleus were measured in order to analyze differences between
both parts. Therefore, the marked regions of interest on images
of histological sections were obtained using a CCD-Camera
(Axiocam MRm, ZEISS, Germany), which was connected to a
light microscope (Axioplan 2 imaging, ZEISS, Germany) and
operated by the Zeiss image analysis software Axiovision (4.8.0).
Three sections per structure, hemisphere and brain were analyzed. Cell densities where measured using parts of the Grey Level
Index (GLI) calculation pipeline to estimate the volume fraction of cell bodies (Wree et al., 1982; Schleicher and Zilles, 1990;
Schleicher et al., 1999).
Therefore we delineated the dentate nucleus into a ventral and
a dorsal partition using ImageJ[1]. In a next step, the density of
cells of each part was measured using in-house software based
on MATLAB 8.1[2]. Both parts differed in the distribution, pattern,
and morphology of neurons (see Results), resulting in a clear-cut
border. Cell bodies were segmented in order to calculate binaryimages (Schleicher and Zilles, 1990; Schleicher et al., 1999), and to
measure the density of cells of each part using in-house software
based on MATLAB 8.1[2]. Subsequently we calculated a quotient
from the area of the segmented cells and the area of the whole
structure [cell area (µm[3])]/[structure area (µm[3])] and compared the mean values between the two parts and hemispheres.
Differences in cell density between the dorsal and ventral dentate nucleus were assessed using the non-parametric WilcoxonSign-Rank test (p < 0.05, Bonferroni-corrected for multiple
comparisons).
In addition, a Folding Index (FI) was estimated to quantify
putative differences between a micro- and macrogyric aspect,

[1http://imagej.nih.gov/ij/](http://imagej.nih.gov/ij/)
[2http://mathworks.com](http://mathworks.com)


-----

which has previously been described (cf. Winkler, 1926; Voogd,
2003). These studies suggested that the dorsal part matches with
the description of a microgyric part, while the ventral represents
a macrogyric part. The FI is comparable to the Gyrification Index
(Zilles et al., 1988, 2013), but estimates the gyrification of nuclei
instead of the whole brain. In a first step, the contour of the dentate nucleus was labeled in images of 10 histological sections per
hemisphere. In a second step, a convex hull representing the outer
border of the dentate nucleus was drawn. The FI was then calculated as the ratio of these two measurements, i.e., FI = [Length
(whole contour)]/[Length (hull contour)].

Analysis of the Subdivision Generation of
Probability Maps and 3D Reconstruction
The delineated nuclei were 3D-reconstructed in each post mortem
brain, and then normalized to the single subject reference
template of the Montreal Neurological Institute to a resolution of 1 mm × 1 mm × 1 mm (stereotaxic MNI-Colin27;
Collins et al., 1994; Holmes et al., 1998; Evans et al., 2012).
In addition, a manual segmentation of the cerebellum was performed using the ITK Snap software (Yushkevich et al., 2006)
to improve the registration of the cerebellum. Superimposing
the individual maps of each nucleus across brains then, yielded
a probabilistic map, indicating how likely each nucleus was
found at each voxel of the stereotaxic MNI-Colin27 template
space.

Mapping Function and Connectivity of the
Delineated Nuclei
Functional interactions during task performance, in the context
of neuroimaging experiments, i.e., co-activations, of the cerebellar nuclei were identified by meta-analytic connectivity modeling
(Eickhoff et al., 2012) using the BrainMap database[3] (Fox and
Lancaster, 2002; Laird et al., 2009, 2011). From this database,
only mapping experiments in healthy subjects were considered,
which yielded approximately 7.500 experiments at the time of
analysis. Among these, all experiments with at least one peak
activation coordinate within cytoarchitectonically defined seed
regions were identified. The number of contributing studies was
marginal for the ventral dentate nucleus (VDN) and dorsal dentate nucleus (DDN) separately or the emboliform and globose
nuclei. Accordingly only minor effects occurred for probing these
subregions. Therefore, the maximum probability map representations of the cytoarchitectonically defined entire dentate nucleus
and interposed nucleus in stereotaxic MNI-Colin27 space were
used as seed regions (Eickhoff et al., 2006). Across these, an
Activation Likelihood Estimation meta-analysis (Eickhoff et al.,
2012; Turkeltaub et al., 2012) was conducted in order to identify
areas of converging activity across these experiments. Evidently,
the highest convergence between studies occurs within the seed
(as all included experiments were selected based upon co-activity
with the seed region). In comparison, significant (p < 0.05)
convergence in areas beyond the seed is indicative of consistent co-activation (i.e., functional connectivity) with the seed
region. The resulting statistically thresholded co-activation map

3www.brainmap.org


(p < 0.05, cluster-level family wise error (FWE) corrected for
multiple comparisons) thus provided the results of the metaanalytic connectivity modeling analysis.
The functional characterization of the cerebellar nuclei was
based on the meta-data available for each neuroimaging experiment included in the BrainMap database. Functional profiles
were determined by identifying taxonomic labels, for which the
probability of finding activation in the respective region was significantly (p < 0.05) higher than by chance. Significance was
established using a binomial test (p < 0.05, corrected for multiple
comparisons; Cieslik et al., 2013; Clos et al., 2013).

## Results

Cytoarchitecture of the Cerebellar Nuclei
An overview of the cytoarchitectonic features of the four cerebellar nuclei including the subdivision of the dentate nucleus is
provided in Figure 1. Figure 2 shows a 3D representation of the
cerebellar nuclei to illustrate the intern-relationship between the
delineated structures.
_The dentate nucleus is the largest and most lateral cerebel-_
lar nucleus. It consisted of densely packed rounded multipolar neurons. Although there was a mixture of cell sizes within
the dentate nucleus, large cells were predominant. The dentate
nucleus appeared as a convoluted band with its hilus located
medially. Based on local differences in cell density and size,
the dentate nucleus could be microscopically subdivided in a
dorsal and ventral part by a clear-cut border, whereby the dorsal part had a significantly higher cell density than the ventral
one. The mean Grey Level Index values, estimating cell density
observer-independently (Wree et al., 1982; Schleicher and Zilles,
1990; Schleicher et al., 1999), and the corresponding SDs were
as follows: left dorsal: 4.09 ± 0.78; right dorsal 4.09 ± 0.74; left
ventral: 3.36 ± 0.62; right ventral: 3.45 ± 0.65 (cf. Figure 3).
Differences between dorsal and ventral parts were significant
(p < 0.05), whereas left–right differences did not reach significance (p > 0.05).
In contrast, no differences were observed with respect to the
FI, which was nearly identical between both parts (FI dorsal average of left and right = 1.69 ± 0.57; ventral average of left and
right = 1.69 ± 0.62; cf. Figure 4).
_The emboliform nucleus was positioned close to the vermis,_
and next to the dentate hilus in all 10 brains. In comparison to
the dentate nucleus, it was formed by less densely packed large
neurons (Figure 1).
_The globose nucleus was also located close to the vermis,_
between the emboliform and the fastigial nucleus. It was the
smallest of the four cerebellar nuclei. In all investigated brains,
its neurons were small and more densely packed as compared
to those in the emboliform nucleus (Figure 1). As previously
described (e.g., Kozlova, 1984), its shape did not follow the name
“globose,” as it often appeared variably elongated.
_The fastigial nucleus was the most medially located cerebellar_
nucleus, located in close vicinity of the fourth ventricle. Starting
at its lateral border, tentacle-like bands of more spikey cells were
visible that spread to the lateral border of the vestibular nucleus.


-----

Volumetric Analysis of the Cerebellar Nuclei
There were no statistically significant effects (p < 0.05) of
sexes or hemisphere on the volumes of any of the delineated nuclei (Table 2). Bilateral mean values for each cerebellar nucleus and their SD are shown in Table 2. The dentate nucleus was the largest cerebellar nucleus, with its dorsal part being about three times smaller than the ventral one.
Nevertheless, this (smaller) dorsal part of the dentate nucleus
was still about two times larger than the emboliform and the
fastigial nuclei. The globose nucleus as the smallest cerebellar
nucleus comprised only approximately a fifth part of the volume
of the emboliform nucleus.


Probabilistic Maps of the Cerebellar Nuclei
All delineated structures were spatially normalized to the stereotaxic MNI-Colin27 single subject template and then combined
across subjects to calculate probabilistic maps of cerebellar
nuclei in stereotaxic space. In correspondence to the localization of the nuclei in each individual brain, all nuclei were
located in the depth of the cerebellar white matter and showed
the expected relative position (laterally: dentate nucleus; paravermal: first emboliform, then globose nucleus; medial: fastigial nucleus). The interindividual variability of the nuclei was
low (Figure 5). There was only a relatively moderate overlap between the probabilistic maps of neighboring nuclei. The


-----

probabilistic maps were used to analyze co-activation patterns in
order to characterize their involvement into different cognitive
functions.

Whole-Brain Co-activation Patterns of the
Cerebellar Nuclei
Co-activation mapping and functional decoding for the combined dentate (ventral and dorsal) and interposed (emboliform
and globose) nuclei were performed. For these analyses, the
regions of interest were defined by the maximum probability map representations of the respective histologically defined
nuclei in stereotaxic MNI-Colin27 space (Eickhoff et al., 2006).


For the dentate nucleus, we found significant (p < 0.05, corrected for multiple comparisons) co-activations with thalamus,
supplementary motor area (SMA) and putamen as well as
within area 44 (Amunts et al., 1999), superior parietal area 7PC
(Scheperjans et al., 2008a), inferior parietal area PFt (Caspers
et al., 2006), and the superior frontal gyrus (SFG). The interposed
nucleus likewise showed, though more limited, co-activation with
the putamen, SMA, area 44 and the SFG (cf. Table 3). Directly
compared with the dentate nucleus (cf. Figure 6), the interposed
nucleus showed a significantly (p < 0.05) higher connectivity
with the left insular lobe [stereotaxic MNI-Colin27: (−40, 0, 2),
cluster size: 104 mm[3]] and the left thalamus [stereotaxic MNIColin27: (−10, −18, 8); cluster size: 90 mm[3]]. In turn, the dentate
nucleus showed higher connectivity with left area 6 [SMA; stereotaxic MNI-Colin27: (−4, −14, 54); cluster size: 215 mm[3]], the left
inferior parietal lobe [Pft; stereotaxic MNI-Colin27: (−46, −40,
56); cluster size: 138 mm[3]], and the inferior frontal gyrus [area
44, stereotaxic MNI-Colin27: (−58, 8, 18); cluster size: 56 mm[3]].
The behavioral domains and paradigm classes significantly
(p < 0.05) associated with the dentate and interposed nuclei
are illustrated in Figure 6. Both structures were found to
be activated by pain. In addition, the interposed nucleus
(green) was significantly (p < 0.05) associated with music
comprehension and visual perception. In turn, the behavioral
domains and paradigm classes of the dentate nucleus (red)
comprised cognitive, speech, and in particular motor related
functions.

## Discussion

Cerebellar nuclei have a strategic position by representing
the almost unique source of output within the cerebellar circuitry (Manto and Oulad Ben Taib, 2010). This study presents
cytoarchitectonically based 3D probability maps of the human


-----

cerebellar nuclei including their application to study their function and functional connectivity. Besides providing information
on the cytoarchitectonic characteristics and precise anatomical
localization of each nucleus, the current study also subdivided
the dentate nucleus into a ventral and a dorsal part based on
cytoarchitectonic criteria. These maps of the cerebellar nuclei
in the stereotaxic MNI-Colin27 reference space are available to
the scientific community[4], and may facilitate interpretation of
_in vivo structural and functional imaging data with respect to_
the microstructural correlates. We here employed these maps to
investigate task-based functional connectivity of the cerebellar
nuclei using meta-analytic co-activation mapping and to perform
a quantitative functional characterization.

Mapping Results
In this study, the borders of the cerebellar nuclei, were delineated
in 10 post mortem brains based on cytoarchitectonic differences,

[4www.fz-juelich.de/inm/inm-1/EN](http://www.fz-juelich.de/inm/inm-1/EN)


and stereotaxic maps were calculated (Table 2 for comparison of
the post mortem and recent MRI data: Diedrichsen et al., 2011).
The current volume of the dentate nucleus is nearly identical
to that reported based on MRI measurements. Small differences
between both estimates may be caused by partial volume effects,
which are more relevant in lower resolution MR images. Three
other previous MRI studies provided substantially larger volumes
(840 mm[3]: Dimitrova et al., 2002, 2006; 900 mm[3]: Deoni and
Catani, 2007). They may overestimate the true volume, caused
by the complex shape of the dentate with its large surface area.
Finally, an older histological estimate yielded a much lower volume of the dentate nucleus, but no shrinkage correction was
applied (155 mm[3]: Höpker, 1951). Still, the volume would be considerably smaller than that of the present study. The volume of the
interposed nucleus of the present study was slightly larger than
previously estimated by MRI (Diedrichsen et al., 2011). The volume of the fastigial nucleus in the Diedrichsen et al. (2011) MRI
atlas finally seemed to be underestimated relative to the current
_post mortem results, but also in comparison to earlier histological_
data (Dejerine and Dejerine-Klumpke, 1901; Jakob, 1928; Jansen
et al., 1958).
To the best of our knowledge, no previous volumetric data
has been presented for the ventral and dorsal subdivisions of
the dentate nucleus and the subdivided interposed (globose and
emboliform) nucleus. While the small size of these structures is
still a major challenge for MRI based delineation in vivo, ultrahigh field MRI with high resolution may allow an even better
delineation in future (Forstmann et al., 2012). In summary, the
estimated volumes for all cerebellar nuclei differ to some degree
between studies of in vivo and post mortem approaches.
Although a comparison of volume data for the subdivision of dentate nucleus is currently not available, we will
here contrast the current post mortem data with some other
methods and studies. A significantly different cell density distribution between the ventral and dorsal part of the dentate
nucleus, with the latter featuring a higher cell density and bigger cells, is in accordance with previous reports (Arras, 1987;
Dum et al., 2002; Voogd, 2003; Timmann, 2012). Albeit transitional areas were reported (Arras, 1987), the present observation revealed a clear-cut border between the ventral and the
dentate nucleus. Interestingly, the reported volume differences
between these two parts of the dentate nucleus, with the ventral
part being about three times larger, may relate to evolutionary
development.
The larger size of the human ventral dentate nucleus may
reflect the general evolutionary trend of “neocorticalization” and
the marked development of higher motor functions and ultimately cognition in the primate lineage (Fix and Treff, 1970).
Accordingly, the (larger) ventral part of the dentate nucleus has
been termed “neo-dentate” (cf. Weidenreich, 1899). Moreover,
the embryogenetic differentiation of the ventral dentate nucleus
developed to the same time as the cerebellar hemispheres, while
development of the dorsal part coincided with that of the vermal
parts and the anterior lobe of the cerebellum (Murofushi, 1974).
From a different angle, it has been shown that in case of neocerebellar atrophy the dorsal dentate nucleus remains untapped
(Brun, 1917). Moreover, the number of interneurons is higher in


-----

TABLE 2 | Mean volumes (mm[3]) and SDs (in brackets) of each cerebellar nucleus of grouped hemispheres and sexes were calculated from the shrinkage
corrected volumes of 10 post mortem brains. Male/female volumes represent the mean volumes of left and right hemisphere volumes. [(pair wise
permutation tests; no differences with p < 0.05); DN: dentate nucleus; DDN: dorsal dentate nucleus; VDN: ventral dentate nucleus; IN: interposed
nucleus; EN: emboliform nucleus; GN: globose nucleus; FN: fastigial nucleus] supplemented by MRI volume data [1]Diedrichsen et al. (2011).

Post mortem MRI[1]

Right Left Male Female Bilateral Right Left

DN 394.5 (94.5) 390.2 (99.3) 433.2 (104.9) 351.5 (75.6) 784.7 (192.7) 366.1 (85.2) 362.8 (89.2)

DDN 93.5 (46.2) 88.7 (42.1) 94.9 (49.6) 87.2 (43.2) 182.1 (88.1) – –

VDN 301.0 (61.3) 301.5 (67.9) 338.3 (57.8) 264.3 (48.6) 602.5 (127.3) – –

IN 59.8 (12.2) 59.0 (11.9) 61.2 (9.1) 57.6 (14.8) 118.7 (23.5) 36.1 (11.4) 35.9 (14.2)

EN 50.2 (12.4) 49.5 (12.2) 50.4 (12.3) 49.3 (13.1) 99.7 (24.0) – –

GN 9.5 (4.0) 9.5 (4.7) 10.8 (5.3) 8.3 (3.1) 19.0 (8.5) – –

FN 45.0 (8.5) 46.4 (13.4) 50.8 (11.6) 40.5 (5.8) 91.4 (20.4) 8.2 (5.2) 9.2 (5.2)


the parvocellular – ventral – part of the dentate nucleus (Arras,
1987), which has been interpreted as a developmental adaptation, described similarly for the isocortex (Schlegelberger and
Braak, 1982). In summary, there is thus converging evidence for a
dorsal–ventral distinction of the human dentate nucleus in which


the larger ventral part has co-evolved with the cerebral cortex (cf.
“neocorticalization” Fix and Treff, 1970) and is related to higher
cognitive-motor functions. Morphological differences have long
been discussed as another aspect of such differentiation (Jansen
et al., 1958; Fix and Treff, 1970; Arras, 1987). Summarized, the


-----

TABLE 3 | Co-activation clusters for the cerebellar nuclei.

Cluster Size Z Stereotaxic MNI-Colin27 Anatomic Localization
(probabilistic anatomical location)

_x_ _y_ _z_

Dentate nucleus[∗] 2163 6.94 −34 +22 +4 Left anterior Insula Lobe

6.26 −26 +18 −4 Left Medial Putamen

6.09 −52 +6 +38 Left Precentral Gyrus (BA 44[1])

5.84 −46 +4 +8 Left Rolandic Operculum

5.78 −48 +6 +6 Left Inferior Frontal Gyrus

5.49 −54 +8 +22 Left Inferior Frontal Gyrus (BA 44[1])

1701 8.32 −2 +2 +54 Left SMA

4.55 +6 +18 +46 Right SMA

4.29 +20 +0 +58 Right Superior Frontal Gyrus

646 8.31 +38 +20 −2 Right Anterior Insula Lobe

5.01 +36 −4 +2 Right Putamen

4.34 +28 +10 −4 Right Putamen

4.18 +24 −2 +2 Right Pallidum

538 8.32 −12 +20 +4 Left Thalamus

8.31 −14 +14 +6 Left Thalamus

4.18 −20 −16 +0 Left Thalamus

516 5.86 +58 +10 +24 Right Inferior Frontal Gyrus (BA 44[1])

5.50 +58 +8 +10 Right Rolandic Operculum (BA 44[1])

420 5.72 −42 −48 +50 Left Inferior Parietal Lobe (7PC[2])
Left Inferior Parietal Lobule (PFt[3])

5.54 −30 −50 +50 Left Inferior Parietal Lobule (7PC[2])

5.50 +58 +8 +10 Right Rolandic Operculum (BA 44[1])

Interposed nucleus[∗] 640 5.49 +20 +0 +58 Right Superior Frontal Gyrus

5.41 +0 +10 +5 Left SMA

4.56 −4 +22 +44 Left SMA

4.44 +8 +4 +60 Left SMA

3.81 +12 +14 +40 Right SMA

3.28 −4 +2 +60 Left SMA (BA 6[4])

307 7.99 −14 −14 +10 Left Thalamus

238 5.53 +28 +10 −4 Right Putamen

4.10 +40 +18 −4 Right Anterior Insula Lobe

3.99 +38 +16 −6 Right Anterior Insula Lobe

266 4.65 −48 +8 +2 Left Rolandic Operculum (BA 44[1])

4.51 −44 +14 −4 Left Anterior Insula Lobe

3.78 −44 +0 +2 Left Insula Lobe

3.45 −44 +24 −4 Left Inferior Frontal Gyrus

243 5.01 −32 +16 +8 Left Insula Lobe

4.65 −22 +6 +2 Left Putamen

_Macroanatomic localization with respect to gyri, sulci, and major subcortical nuclei; localization with respect to cytoarchitectonic probabilistic maps if available._
_*pFDR < 0.05._ [1]Amunts et al. (1999), [2]Scheperjans et al. (2008b), [3]Caspers et al. (2008), [4]Geyer (2004).


magnocellular dorsal part has been described as microgyric and
the parvocellular ventral part as macrogyric (e.g., Voogd, 2003).
In contrast to previous reports on a macro- and microgyric part
within the dentate nucleus (Winkler, 1926; Voogd, 2003) no
differences were found with respect to the FI as a measure of
“gyrification.” This finding, in turn, is in accordance with another
more recent study, where a gyrification difference within the dentate was only found in macaques but not in human brains (Sultan
et al., 2010). Finally it should be mentioned, that the literature
provides evidence for a more subtle and somatotopic distinction
of the cerebellar cortex (Hampson et al., 1946; Snider and Eldred,


1952; Grodd et al., 2001). It can therefore be hypothesized that
this may also apply to the cerebellar nuclei, which are interconnected with the different parts of the cerebellar cortex. Arras
(1987) reported a transitional area between the ventral and dorsal dentate nucleus. Results of the present observation did not
support this assumption, and no differences in cytoarchitecture
have been observed in-between the dorsal and the ventral parts.
Other studies point toward a somatotopic organization of the
dentate nucleus in human (in vivo) and monkeys (tracer studies;
Dum et al., 2002; Dum and Strick, 2003; Kuper et al., 2013). Dum
et al. (2002) used tracer injections into the primary motor cortex


-----

to provide evidence for somatotopically organized connectivity
patterns in the dorsal dentate nucleus (from rostral to caudal:
arm, leg, and face), and somatotopic connectivity with the premotor cortex and in the middle third of the caudate. A third
somatotopically organized pattern of connections to prefrontal
areas 46, 9, and 7 was observed in the ventral dentate nucleus.
In the present study we did not find consistent cytoarchitectonic
evidence for further subdivisions of the dentate nucleus. This,


however, does not rule out potential distinctions that may emerge
from, e.g., myeloarchitecture or multi-receptor mapping.

Co-activation Patterns of the Cerebellar
Nuclei
Recent studies showed that the cortex of the cerebellar hemispheres, in particular Crus I and Crus II (lobolus VIIA; cf.
Schmahmann et al., 1999) is strongly involved in cognitive


-----

functioning (Kelly and Strick, 2003; Balsters et al., 2013; see also
Tomlinson et al., 2013 for an overview). These structures, in
turn, are linked to the ventral dentate nuclei as described above
(Voogd, 1964; Rossum, 1969). In line with this model and nonhuman approaches (e.g., Strick et al., 2009), the present study
showed the dentate nucleus to be engaged in motor-related and
cognitive processes. While single Tracer studies (Dum et al.,
2002) distinguished a ventral and a dorsal part of the dentate
nucleus, the meta-analysis shown here represents the functional
associations and connections of the entire dentate nucleus, due to
the limited number of contributing studies when analyzing subdivisions. Nevertheless, we found the dentate nucleus involved
in basal executive as well as in higher order motor and cognitive functions. The results of our analysis on the entire dentate
nucleus are in line with this focused investigation and primate
data. In addition, the functional decoding not only showed an
involvement of the dentate nucleus in cognitive and motor tasks,
but also with respect to pain processing. Cerebellar involvement in pain-perception has been described earlier (Glickstein,
2007; Timmann and Daum, 2007; Strick et al., 2009). In general, the delineated functional connectivity of the dentate nucleus
matches well with reports from invasive approaches dealing with
structural connectivity mapping in non-human primates (see a
review by Dum et al., 2002), even though no interactions with
the primary motor cortex was observed in our findings. We did,
however, observe significant (p < 0.05) co-activation between
the dentate nucleus and the SMA. This finding matches with
previous descriptions, which show that neurons from the dorsal
“motor” domain of the dentate nucleus in monkey brains project
to the SMA (Akkal et al., 2007). The co-activations of the dentate nucleus with the inferior and anterior parietal cortex are in
line with tracing data revealing a connection between the parietal
cortex and the (ventral) dentate nucleus (Dum et al., 2002). While
there is no primate data to this end, the link between the dentate
nucleus and speech as well as its co-activation with left BA 44 is
in good agreement with a previous fMRI study (Thurling et al.,
2012). Finally, it has been argued, that a particular function of the
cerebellar hemisphere, which remits its output throughout the
dentate nucleus, is rhythm perception and memory (Jerde et al.,
2011; Pecenka et al., 2013). The current finding of an association
between the dentate nucleus and music comprehension supports
this view.
Only a small number of previous studies have reported on
anatomy, function and connectivity of the interposed nuclei,
most likely due to difficulties in the precise localization of these
small structures. It has been reported that the paravermal interposed nuclei may be related to associative motor learning, i.e.,
eye blink reflex (Gerwig et al., 2003; Parker et al., 2009). The
present study found that the interposed nuclei are associated with
visual perception and attention as well as visuomotor tasks, which
would be in line with these previous findings. Likewise, the association to somesthetic domain resonates well with older accounts
which postulated a role for the interposed nuclei in (disturbed)
sensory perception and cerebellar tremor (Vilis and Hore, 1977).
Like the dentate nucleus, also the interposed nucleus features
co-activations with the SMA. The SMA represents a key structure for bimanual movement coordination and reach-to-grasp


functions (Wilson et al., 2014) and there is also strong evidence
from human and monkey studies that the interposed nucleus
plays an important role for reaching-to-grasp movements (van
Kan et al., 1994; Monzee and Smith, 2004; Kuper et al., 2011b).
Given that, we would thus argue, that these interactions may
play a particular role in the cortico-cerebellar tuning of complex,
coordinated arm, and hand movements.

## Conclusion

We here reported on the first probabilistic atlas of the human
cerebellar nuclei based on a cytoarchitectonic histological examination in 10 post mortem brains. The probabilistic maps in
the stereotaxic MNI-Colin27 space provide new opportunities to
relate structure, function, and dysfunction of the cerebellar nuclei
as obtained in the living human brain to microscopically defined
nuclei. To foster their use, the proposed maps will be integrated
into the JuBrain atlas and freely distributed as part of the SPM
Anatomy Toolbox[5].

## Author Contributions

ST performed the cytoarchitectonic mapping, interpretation of
data and wrote the first draft of the manuscript.
SB contributed to the development of methods for parcellation
and analysis and revised the manuscript.
SE contributed to the meta-analytic connectivity modeling analysis and revised the manuscript.
HM contributed to the 3D reconstruction of the postmortem
brains, their transformation into the stereotaxic MNI-Colin27
space and the computation of the probabilistic maps.
MM contributed to interpretation of data for the work and
revised the manuscript.
KA contributed to the design of the study, the development
of methods for parcellation and analysis, the interpretation of
results and writing the manuscript.
All authors have approved the final version of the work to be
published and agree to be accountable for all aspects of the work
in ensuring that questions related to the accuracy or integrity
of any part of the work are appropriately investigated and
resolved.

## Acknowledgments

This study was supported by the Deutsche
Forschungsgemeinschaft (DFG, EI 816/4-1, LA 3071/3-1;
EI 816/6-1.), the National Institute of Mental Health (R01MH074457), and the European Union Seventh Framework
Programme (FP7/2007-2013) under grant agreement no. 604102
(Human Brain Project). The authors thank Peter Pieperhoff,
David Gräßel, and Karl Zilles for helpful discussions.

[5http://www.fz-juelich.de/SharedDocs/Downloads/INM/INM-1/DE/Toolbox](http://www.fz-juelich.de/SharedDocs/Downloads/INM/INM-1/DE/Toolbox)


-----

## References

Akkal, D., Dum, R. P., and Strick, P. L. (2007). Supplementary motor area and
presupplementary motor area: targets of basal ganglia and cerebellar output.
_J. Neurosci. 27, 10659–10673. doi: 10.1523/JNEUROSCI.3134-07.2007_
Amunts, K., Schleicher, A., Bürgel, U., Mohlberg, H., Uylings, H. B.,
Zilles, K., et al. (1999). Broca’s region revisited: cytoarchitecture and intersubject variability. J. Comp. Neurol. 412, 319–341. doi: 10.1002/(SICI)10969861(19990920)412:2<319::AID-CNE10>3.0.CO;2-7
Amunts, K., Schleicher, A., and Zilles, K. (2007). Cytoarchitecture of the
cerebral cortex-more than localization. Neuroimage 37, 1061–1068. doi:
10.1016/j.neuroimage.2007.02.037
Arras, C. (1987). Architektonische Gliederung des Nucleus dentatus im Gehirn des
_Menschen. Dissertation, University of Cologne, Cologne._
Balsters, J. H., Whelan, C. D., Robertson, I. H., and Ramnani, N. (2013).
Cerebellum and cognition: evidence for the encoding of higher order rules.
_Cereb. Cortex 23, 1433–1443. doi: 10.1093/cercor/bhs127_
Braak, H., and Braak, E. (1983). Morphological studies of local circuit neurons
in the cerebellar dentate nucleus of man. Hum. Neurobiol. 2, 49–57. doi:
10.1016/j.jtbi.2015.01.024˚u2.30
Brun, R. (1917). Zur Kenntnis der Bildungsfehler des Kleinhirns. Schweiz. Arch.
_Neurol. Psychiatr. 1, 61–123. doi: 10.1007/BF01814443_
Cajal, R. Y., and Santiago. (1953). Histologie du SysteÌme Nerveux de L’homme
_and des Verteìbreìs. Madrid: Consejo Superior de Investigaciones Cientiìficas,_
Instituto Ramoìn y Cajal.
Carpenter, M. B. (1991). Core Text of Neuroanatomy. Baltimore, MD: Williams &
Wilkins. doi: 10.1007/s00429-008-0195-z
Caspers, S., Eickhoff, S. B., Geyer, S., Scheperjans, F., Mohlberg, H., Zilles, K., et al.
(2008). The human inferior parietal lobule in stereotaxic space. Brain Struct.
_Funct. 212, 481–495. doi: 10.1016/j.neuroimage.2006.06.054_
Caspers, S., Geyer, S., Schleicher, A., Mohlberg, H., Amunts, K., Zilles, K., et al.
(2006). The human inferior parietal cortex: cytoarchitectonic parcellation
and interindividual variability. Neuroimage 33, 430–448. doi: 10.1001/archneurpsyc.1955.02330180071008
Chambers, W. W., and Sprague, J. M. (1955). Functional localization in the cerebellum. II. Somatotopic organization in cortex and nuclei. AMA Arch. Neurol.
_Psychiatry 74, 653–680. doi: 10.1093/cercor/bhs256_
Cieslik, E. C., Zilles, K., Caspers, S., Roski, C., Kellermann, T. S., Jakobs, O., et al.
(2013). Is there “one” DLPFC in cognitive action control? Evidence for heterogeneity from co-activation-based parcellation. Cereb. Cortex 23, 2677–2689.
doi: 10.1093/cercor/bhs256
Clos, M., Amunts, K., Laird, A. R., Fox, P. T., and Eickhoff, S. B. (2013).
Tackling the multifunctional nature of Broca’s region meta-analytically: coactivation-based parcellation of area 44. Neuroimage 83, 174–188. doi:
10.1016/j.neuroimage.2013.06.041
Collins, D. L., Neelin, P., Peters, T. M., and Evans, A. C. (1994). Automatic 3D
intersubject registration of MR volumetric data in standardized Talairach space.
_J. Comput. Assist. Tomogr. 18, 192–205. doi: 10.1097/00004728-199403000-_
00005
Dejerine, J., and Dejerine-Klumpke, A. (1901). Anatomie des Centres Nerveux.
Paris: Rueff.
Deoni, S. C., and Catani, M. (2007). Visualization of the deep cerebellar nuclei using
quantitative T1 and rho magnetic resonance imaging at 3 Tesla. Neuroimage 37,
1260–1266. doi: 10.1016/j.neuroimage.2007.06.036
Diedrichsen, J., Maderwald, S., Küper, M., Thürling, M., Rabe, K., Gizewski,
E. R., et al. (2011). Imaging the deep cerebellar nuclei: a probabilistic atlas and normalization procedure. Neuroimage 54, 1786–1794. doi:
10.1016/j.neuroimage.2010.10.035
Di Ieva, A., Tschabitscher, M., Galzio, R. J., Grabner, G., Kronnerwetter, C.,
Widhalm, G., et al. (2011). The veins of the nucleus dentatus:
anatomical and radiological findings. _Neuroimage_ 54, 74–79. doi:
10.1016/j.neuroimage.2010.07.045
Dimitrova, A., Weber, J., Redies, C., Kindsvater, K., Maschke, M., Kolb, F. P., et al.
(2002). MRI atlas of the human cerebellar nuclei. Neuroimage 17, 240–255. doi:
10.1006/nimg.2002.1124
Dimitrova, A., Zeljko, D., Schwarze, F., Maschke, M., Gerwig, M., Frings, M., et al.
(2006). Probabilistic 3D MRI atlas of the human cerebellar dentate/interposed
nuclei. Neuroimage 30, 12–25. doi: 10.1016/j.neuroimage.2005.09.020


Dum, R. P., Li, C., and Strick, P. L. (2002). Motor and nonmotor domains in
the monkey dentate. Ann. N. Y. Acad. Sci. 978, 289–301. doi: 10.1111/j.17496632.2002.tb07575.x
Dum, R. P., and Strick, P. L. (2003). An unfolded map of the cerebellar dentate
nucleus and its projections to the cerebral cortex. J. Neurophysiol. 89, 634–639.
doi: 10.1152/jn.00626.2002
Eickhoff, S. B., Bzdok, D., Laird, A. R., Kurth, F., and Fox, P. T. (2012). Activation
likelihood estimation meta-analysis revisited. Neuroimage 59, 2349–2361. doi:
10.1016/j.neuroimage.2011.09.017
Eickhoff, S. B., Schleicher, A., Zilles, K., and Amunts, K. (2006). The human parietal operculum. I. Cytoarchitectonic mapping of subdivisions. Cereb. Cortex 16,
254–267. doi: 10.1093/cercor/bhi105
Eickhoff, S. B., Stephan, K. E., Mohlberg, H., Grefkes, C., Fink, G. R., Amunts, K.,
et al. (2005). A new SPM toolbox for combining probabilistic cytoarchitectonic maps and functional imaging data. Neuroimage 25, 1325–1335. doi:
10.1016/j.neuroimage.2004.12.034
Evans, A. C., Janke, A. L., Collins, D. L., and Baillet, S. (2012). Brain templates and
atlases. Neuroimage 62, 911–922. doi: 10.1016/j.neuroimage.2012.01.024
Fix, J. D., and Treff, W. M. (1970). Structural principles of the phylogenetic development of the cerebellar nuclei in primates. Acta Anat. (Basel) 76, 337–351. doi:
10.1159/000143501
Forstmann, B. U., Keuken, M. C., Jahfari, S., Bazin, P. L., Neumann, J., Schäfer, A.,
et al. (2012). Cortico-subthalamic white matter tract strength predicts interindividual efficacy in stopping a motor response. Neuroimage 60, 370–375. doi:
10.1016/j.neuroimage.2011.12.044
Fox, P. T., and Lancaster, J. L. (2002). Opinion: mapping context and content: the
BrainMap model. Nat. Rev. Neurosci. 3, 319–321. doi: 10.1038/nrn789
Gans, A. (1924). Beitrag zur kenntnis des aufbaus des nucleus dentatus aus
zwei teilen, namentlich auf grund von untersuchungen mit der eisenreaktion.
_Z. Gesamte Neurol. Psychiatr. 93, 750–755. doi: 10.1007/BF02900080_
Gerwig, M., Dimitrova, A., Kolb, F. P., Maschke, M., Brol, B., Kunnel, A., et al.
(2003). Comparison of eyeblink conditioning in patients with superior and posterior inferior cerebellar lesions. Brain 126, 71–94. doi: 10.1093/brain/awg011
Geyer, S. (2004). The microstructural border between the motor and the cognitive
domain in the human cerebral cortex. Adv. Anat. Embryol. Cell Biol. 174:I–VIII,
1–89. doi: 10.1007/978-3-642-18910-4_1
Glickstein, M. (2007). What does the cerebellum really do? Curr. Biol. 17, R824–
R827. doi: 10.1016/j.cub.2007.08.009
Grodd, W., Hulsmann, E., Lotze, M., Wildgruber, D., and Erb, M. (2001).
Sensorimotor mapping of the human cerebellum: fMRI evidence of somatotopic organization. Hum. Brain Mapp. 13, 55–73. doi: 10.1002/hbm.1025
Hampson, J. L., Harrison, C. R., and Woolsey, C. N. (1946). Somatotopic localization in the cerebellum. Fed. Proc. 5, 41.
Hassler, R. (1950). Cerebellar projections to the midbrain and thalamus in man.
_Dtsch. Z. Nervenheilkd. 163, 629–671. doi: 10.1007/BF00213160_
Holmes, C. J., Hoge, R., Collins, L., Woods, R., Toga, A. W, Evans, A. C., et al.
(1998). Enhancement of MR images using registration for signal averaging.
_J. Comput. Assist. Tomogr. 22, 324–333. doi: 10.1097/00004728-199803000-_
00032
Homke, L., Amunts, K., Bönig, L., Fretz, C., Binkofski, F., Zilles, K., et al.
(2009). Analysis of lesions in patients with unilateral tactile agnosia using
cytoarchitectonic probabilistic maps. Hum. Brain Mapp. 30, 1444–1456. doi:
10.1002/hbm.20617
Höpker, W. (1951). Das Altern des nucleus dentatus. Z. Altersforsch. 5, 256–277.
Icardo, J. M., Ojeda, J. L., Garcia-Porrero, J. A., and Hurle, J. M. (1982). The cerebellar arteries: cortical patterns and vascularization of the cerebellar nuclei. Acta
_Anat. (Basel) 113, 108–116. doi: 10.1159/000145545_
Jakob, A. (1928). “Das Kleinhirn,” in Möllendorfs Handbuch der Mikroskopischen
_Anatomie des Menschen, ed. W. V. Möllendorff (Berlin: Springer), 674–916. doi:_
10.1007/978-3-642-66443-4_12
Jansen, J., and Brodal, A. (1942). Experimental Studies on the Intrinsic Fibers of the
_Cerebellum: The Cortico-Nuclear Projection in the Rabbit and the Monkey. Oslo:_
Dybwad.
Jansen, J., Brodal, A., Möllendorff, W. V., and Bargmann, W. (1958). Das Kleinhirn.
Berlin: Springer. doi: 10.1007/978-3-662-21749-8
Jerde, T. A., Childs, S. K., Handy, S. T., Nagode, J. C., and Pardo, J. V. (2011).
Dissociable systems of working memory for rhythm and melody. Neuroimage
57, 1572–1579. doi: 10.1016/j.neuroimage.2011.05.061


-----

Kelly, R. M., and Strick, P. L. (2003). Cerebellar loops with motor cortex and
prefrontal cortex of a nonhuman primate. J. Neurosci. 23, 8432–8444. doi:
10.3791/52302
Kölliker, A. V. (1889). Handbuch der Gewebelehre des Menschen. Leipzig:
Engelmann.
Kozlova, G. P. (1984). Individual anatomical variations in cerebellar nuclei.
_Neurosci. Behav. Physiol. 14, 63–67. doi: 10.1007/BF01148733_
Kuper, M., Dimitrova, A., Thürling, M., Maderwald, S., Roths, J., Elles, H. G.,
et al. (2011a). Evidence for a motor and a non-motor domain in the
human dentate nucleus-an fMRI study. Neuroimage 54, 2612–2622. doi:
10.1016/j.neuroimage.2010.11.028
Kuper, M., Hermsdörfer, J., Brandauer, B., Thürling, M., Schoch, B., Theysohn, N.,
et al. (2011b). Lesions of the dentate and interposed nuclei are associated with
impaired prehension in cerebellar patients. Neurosci. Lett. 499, 132–136. doi:
10.1016/j.neulet.2011.05.055
Kuper, M., Thurling, M., Maderwald, S., Ladd, M. E., and Timmann, D.
(2012). Structural and functional magnetic resonance imaging of the
human cerebellar nuclei. Cerebellum 11, 314–324. doi: 10.1007/s12311-0100194-5
Kuper, M., Wünnemann, M. J., Thürling, M., Stefanescu, R. M., Maderwald, S.,
Elles, H. G., et al. (2013). Activation of the cerebellar cortex and the dentate
nucleus in a prism adaptation fMRI study. Hum. Brain Mapp. 35, 1574–1586.
doi: 10.1002/hbm.22274
Laird, A. R., Eickhoff, S. B., Kurth, F., Fox, P. M., Uecker, A. M., Turner, J. A.,
et al. (2009). ALE meta-analysis workflows via the brainmap database: progress
towards a probabilistic functional brain atlas. Front. Neuroinformatics 3:23. doi:
10.3389/neuro.3311.3023.2009
Laird, A. R., Eickhoff, S. B., Mickle Fox, P., Uecker, A. M., Ray, K. L., Saenz,
J. J. Jr., et al. (2011). The BrainMap strategy for standardization, sharing, and
meta-analysis of neuroimaging data. BMC Res. Notes 4:349. doi: 10.1186/17560500-4-349
Lavezzi, A. M., Corna, M., Matturri, L., and Santoro, F. (2009). Neuropathology
of the Guillain-Mollaret triangle (dentato-rubro-olivary network) in sudden unexplained perinatal death and SIDS. Open Neurol. J. 3, 48–53. doi:
10.2174/1874205X00903010048
Lugaro, E. (1895). Sulla strutura del nucleo dentate del cerveletto nell’ uomo.
_Monit. Zoologico Ital. 6, 5–12._
Manto, M.-U. (2002). The Cerebellum and its Disorders. Cambridge; New York, NY:
Cambridge University Press.
Manto, M. U. (2010). _Cerebellar_ _Disorders_ _A_ _Practical_ _Approach_ _to_
_Diagnosis and Management. Cambridge: Cambridge University Press. doi:_
10.1017/CBO9780511750557
Manto, M., and Oulad Ben Taib, N. (2010). Cerebellar nuclei: key roles for strategically located structures. Cerebellum 9, 17–21. doi: 10.1007/s12311-010-0159-8
Maschke, M., Erichsen, M., Drepper, J., Jentzen, W., Müller, S. P., Kolb, F. P., et al.
(2003). Cerebellar representation of the eyeblink response as revealed by PET.
_Neuroreport 14, 1371–1374. doi: 10.1097/00001756-200307180-00018_
McNaughton, S., Timmann, D., Watts, S., and Hore, J. (2004). Overarm throwing
speed in cerebellar subjects: effect of timing of ball release. Exp. Brain Res. 154,
470–478. doi: 10.1007/s00221-003-1677-0
Merker, B. (1983). Silver staining of cell bodies by means of physical development.
_J. Neurosci. Methods 9, 235–241. doi: 10.1016/0165-0270(83)90086-9_
Mihajlovic, P., and Zecevic, N. (1986). Development of the human dentate nucleus.
_Hum. Neurobiol. 5, 189–197._
Monzee, J., and Smith, A. M. (2004). Responses of cerebellar interpositus neurons to predictable perturbations applied to an object held in a precision grip.
_J. Neurophysiol. 91, 1230–1239. doi: 10.1152/jn.01120.2002_
Murofushi, K. (1974). Normal development and dysgenesias of the dentate nucleus
and inferior olive. Acta Neuropathol. 27, 317–328. doi: 10.1007/BF00690696
Nieuwenhuys, R., Huijzen, C., and Voogd, J. (2008). The Human Central Nervous
_System. Berlin: Springer. doi: 10.1007/978-3-540-34686-9_
O’Rahilly, R., and Müller, F. (2006). The Embryonic Human Brain : An
_Atlas_ _of_ _Developmental_ _Stages._ Hoboken, NJ: Wiley-Interscience. doi:
10.1002/0471973084
Parker, K. L., Zbarska, S., Carrel, A. J., and Bracha, V. (2009). Blocking
GABAA neurotransmission in the interposed nuclei: effects on conditioned and
unconditioned eyeblinks. Brain Res. 1292, 25–37. doi: 10.1016/j.brainres.2009.
07.053


Pecenka, N., Engel, A., and Keller, P. E. (2013). Neural correlates of auditory temporal predictions during sensorimotor synchronization. Front. Hum. Neurosci.
7:380. doi: 10.3389/fnhum.2013.00380
Ristanovic, D., Milosevic, N. T., Stefanovic, B. D., Maric, D. L., and Rajkovic, K.
(2010). Morphology and classification of large neurons in the adult human dentate nucleus: a qualitative and quantitative analysis of 2D images. Neurosci. Res.
67, 1–7. doi: 10.1016/j.neures.2010.01.002
Rossum, J. V. (1969). Corticonuclear and Corticovestibular Projections of the
_Cerebellum : An Experimentel Investigation of the Anterior Lobe, the Simple_
_Lobule and the Caudal Vermis in the Rabbit. Assen: Van Gorcum._
Rub, U., Brunt, E. R., and Deller, T. (2008). New insights into the
pathoanatomy of spinocerebellar ataxia type 3 (Machado-Joseph disease). _Curr._ _Opin._ _Neurol._ 21, 111–116. doi: 10.1097/WCO.0b013e32
82f7673d
Rub, U., Schöls, L., Paulsonet, H. L., Auburger, G., Kermer, P., Jen, J. C., et al.
(2013). Clinical features, neurogenetics and neuropathology of the polyglutamine spinocerebellar ataxias type 1, 2, 3, 6 and 7. Prog. Neurobiol. 104, 38–66.
doi: 10.1016/j.pneurobio.2013.01.001
Scheperjans, F., Eickhoff, S. B., Hömke, L., Mohlberg, H., Hermann, K.,
Amunts, K., et al. (2008a). Probabilistic maps, morphometry, and variability
of cytoarchitectonic areas in the human superior parietal cortex. Cereb. Cortex
18, 2141–2157. doi: 10.1093/cercor/bhm241
Scheperjans, F., Hermann, K., Eickhoff, S. B., Amunts, K., Schleicher, A.,
Zilles, K., et al. (2008b). Observer-independent cytoarchitectonic mapping of
the human superior parietal cortex. Cereb. Cortex 18, 846–867. doi: 10.1093/cercor/bhm116
Scherzed, W., Brunt, E. R., Heinsen, H., de Vos, R. A., Seidel, K., Bürk, K., et al.
(2012). Pathoanatomy of cerebellar degeneration in spinocerebellar ataxia type
2 (SCA2) and type 3 (SCA3). Cerebellum 11, 749–760. doi: 10.1007/s12311-0110340-8
Schlegelberger, T., and Braak, H. (1982). The packing density of supragranular pigment-laden stellate cells in phylogenetically older and
newer portions of the human telencephalic cortex. J. Hirnforsch. 23,
49–53.
Schleicher, A., Amunts, K., Geyer, S., Morosan, P., and Zilles, K. (1999). Observerindependent method for microstructural parcellation of cerebral cortex: a
quantitative approach to cytoarchitectonics. Neuroimage 9, 165–177. doi:
10.1006/nimg.1998.0385
Schleicher, A., and Zilles, K. (1990). A quantitative approach to cytoarchitectonics: analysis of structural inhomogeneities in nervous tissue using
an image analyser. J. Microsc. 157, 367–381. doi: 10.1111/j.1365-2818.1990.
tb02971.x
Schmahmann, J. D. (2010). The role of the cerebellum in cognition and emotion:
personal reflections since 1982 on the dysmetria of thought hypothesis, and its
historical evolution from theory to therapy. Neuropsychol. Rev. 20, 236–260.
doi: 10.1007/s11065-010-9142-x
Schmahmann, J. D., and Caplan, D. (2006). Cognition, emotion and the cerebellum. Brain 129, 290–292. doi: 10.1093/brain/awh729
Schmahmann, J. D., Doyon, J., McDonald, D., Holmes, C., Lavoie, K., Hurwitz,
A. S., et al. (1999). Three-dimensional MRI atlas of the human cerebellum in proportional stereotaxic space. Neuroimage 10, 233–260. doi:
10.1006/nimg.1999.0459
Schulz, J. B., and Pandolfo, M. (2013). 150 years of Friedreich ataxia: from its
discovery to therapy. J. Neurochem. 126(Suppl. 1), 1–3. doi: 10.1111/jnc.12327
Snider, R. S., and Eldred, E. (1952). Cerebrocerebellar relationships in the monkey.
_J. Neurophysiol. 15, 27–40._
Stilling, B. (1864). Untersuchungen über den Bau des Kleinen Gehirns des Menschen.
Cassel: Kay.
Strick, P. L., Dum, R. P., and Fiez, J. A. (2009). Cerebellum and
nonmotor function. _Annu._ _Rev._ _Neurosci._ 32, 413–434. doi:
10.1146/annurev.neuro.31.060407.125606
Sultan, F., Hamodeh, S., and Baizer, J. S. (2010). The human dentate
nucleus: a complex shape untangled. Neuroscience 167, 965–968. doi:
10.1016/j.neuroscience.2010.03.007
Thurling, M., Hautzel, H., Küper, M., Stefanescu, M. R., Maderwald, S., Ladd, M. E.,
et al. (2012). Involvement of the cerebellar cortex and nuclei in verbal and visuospatial working memory: a 7 T fMRI study. Neuroimage 62, 1537–1550. doi:
10.1016/j.neuroimage.2012.05.037


-----

Thurling, M., Küper, M., Stefanescu, R., Maderwald, S., Gizewski, E. R., Ladd, M. E.,
et al. (2011). Activation of the dentate nucleus in a verb generation task: a 7T
MRI study. Neuroimage 57, 1184–1191. doi: 10.1016/j.neuroimage.2011.05.045
Timmann, D. (2012). Contribution of the cerebellum to cognition. Fortschr.
_Neurol. Psychiatr. 80, 44–52. doi: 10.1055/s-0031-1282022_
Timmann, D., and Daum, I. (2007). Cerebellar contributions to cognitive functions: a progress report after two decades of research. Cerebellum 6, 159–162.
doi: 10.1080/14734220701496448
Timmann, D., Dimitrova, A., Hein-Kropp, C., Wilhelm, H., and Dorfler, A. (2003).
Cerebellar agenesis: clinical, neuropsychological and MR findings. Neurocase 9,
402–413. doi: 10.1076/neur.9.5.402.16555
Tomlinson, S. P., Davis, N. J., and Bracewell, R. M. (2013). Brain stimulation studies of non-motor cerebellar function: a systematic review.
_Neurosci._ _Biobehav._ _Rev._ 37, 766–789. doi: 10.1016/j.neubiorev.2013.
03.001
Tschabitscher, M. (1979). [Veins of the human cerebellum]. Acta Anat. (Basel) 105,
344–366. doi: 10.1159/000145139
Tschabitscher, M., and Perneczky, A. (1976). [Vascularization of cerebellar dentate
nucleus]. Verh. Anat. Ges. 70, 393–400.
Turkeltaub, P. E., Eickhoff, S. B., Laird, A. R., Fox, M., Wiener, M., Fox, P.,
et al. (2012). Minimizing within-experiment and within-group effects in activation likelihood estimation meta-analyses. Hum. Brain Mapp. 33, 1–13. doi:
10.1002/hbm.21186
van Kan, P. L., Horn, K. M., and Gibson, A. R. (1994). The importance of hand use
to discharge of interpositus neurones of the monkey. J. Physiol. 480, 171–190.
doi: 10.1113/jphysiol.1994.sp020351
Vilis, T., and Hore, J. (1977). Effects of changes in mechanical state of
limb on cerebellar intention tremor. J. Neurophysiol. 40, 1214–1224. doi:
10.1136/jnnp.2004.044305
Vogt, C., and Vogt, O. (1942). Morphologische Gestaltungen unter Normalen und
_Pathogenen Bedingungen : Ein Hirnanatomischer Beitrag zu ihrer Kenntnis._
Leipzig: Barth.
Voogd, J. (1964). The Cerebellum of the Cat: Structure and Fibre Connexions. Assen:
Van Gorcum.
Voogd, J. (2003). The human cerebellum. J. Chem. Neuroanat. 26, 243–252. doi:
10.1016/j.jchemneu.2003.07.005


Weidenreich, F. (1899). Zur Anatomie der Centralen Kleinhirnkerne der Säuger.
Stuttgart: Nägele.
Wilson, T. W., Kurz, M. J., and Arpin, D. J. (2014). Functional specialization within the supplementary motor area: a fNIRS study of bimanual
coordination. Neuroimage 85(Pt 1), 445–450. doi: 10.1016/j.neuroimage.2013.
04.112
Winkler, C. (1926). Handboek der Neurologie. Haarlem: Bohn.
Wree, A., Schleicher, A., and Zilles, K. (1982). Estimation of volume fractions
in nervous tissue with an image analyzer. J. Neurosci. Methods 6, 29–43. doi:
10.1016/0165-0270(82)90014-0
Yamaguchi, K., Goto, N., and Yamamoto, T. Y. (1989). Development of human
cerebellar nuclei. Morphometric study. Acta Anat. (Basel) 136, 61–68. doi:
10.1159/000146799
Yushkevich, P. A., Piven, J., Hazlett, H. C., Smith, R. G., Ho, S., Gee,
J. C., et al. (2006). User-guided 3D active contour segmentation of
anatomical structures: significantly improved efficiency and reliability. _Neuroimage_ 31, 1116–1128. doi: 10.1016/j.neuroimage.2006.
01.015
Zilles, K., Armstrong, E., Schleicher, A., and Kretschmann, H. J. (1988). The
human pattern of gyrification in the cerebral cortex. Anat. Embryol. (Berl.) 179,
173–179. doi: 10.1007/BF00304699
Zilles, K., Palomero-Gallagher, N., and Amunts, K. (2013). Development of cortical folding during evolution and ontogeny. Trends Neurosci. 36, 275–284. doi:
10.1016/j.tins.2013.01.006

**Conflict of Interest Statement: The authors declare that the research was con-**
ducted in the absence of any commercial or financial relationships that could be
construed as a potential conflict of interest.

_Copyright © 2015 Tellmann, Bludau, Eickhoff, Mohlberg, Minnerop and Amunts._
_[This is an open-access article distributed under the terms of the Creative Commons](http://creativecommons.org/licenses/by/4.0/)_
_[Attribution License (CC BY). The use, distribution or reproduction in other forums](http://creativecommons.org/licenses/by/4.0/)_
_is permitted, provided the original author(s) or licensor are credited and that the_
_original publication in this journal is cited, in accordance with accepted academic_
_practice. No use, distribution or reproduction is permitted which does not comply_
_with these terms._


-----

