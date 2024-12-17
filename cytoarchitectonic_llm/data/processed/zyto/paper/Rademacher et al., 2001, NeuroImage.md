# Probabilistic Mapping and Volume Measurement of Human Primary Auditory Cortex

J. Rademacher,*,†,1 P. Morosan,†,‡ T. Schormann,‡ A. Schleicher,‡ C. Werner,*
H.-J. Freund,* and K. Zilles†,‡

*Department of Neurology and ‡C&O Vogt Institute for Brain Research, Heinrich-Heine University, 40225 Du¨sseldorf;
_and †Institute of Medicine, Research Center Ju¨lich, Ju¨lich, Germany_

Received June 30, 2000; published online February 2, 2001


**Despite their potential utility in clinical and re-**
**search settings, the range of intra- and interindividual**
**variations in size and location of cytoarchitectonically**
**defined human primary auditory cortex (PAC) is**
**largely unknown. This study demonstrates that gyral**
**patterns and the size and location of PAC vary inde-**
**pendently to a considerable degree. Thus, the cytoar-**
**chitectonic borders of PAC cannot be reliably inferred**
**from macroscopic—MR visible—anatomy. Given the**
**remarkable topographical variability of architectonic**
**areal borders, standard brain mapping which is made**
**solely on the basis of macroanatomic landmarks may**
**lead** **to** **structural–functional** **mismatch.** **Conse-**
**quently, interpretations of individual auditory activ-**
**ity patterns might often be inaccurate. In view of the**
**anatomic** **discrepancies,** **we** **generated** **probability**
**maps of PAC in which the degree of intersubject over-**
**lap in each stereotaxic position was quantified. These**
**maps show that the location of PAC in Talairach space**
**differs considerably between hemispheres and indi-**
**viduals. In contrast to earlier cytoarchitectonic work**
**which is based in most cases on studies of single**
**brains, our systematic approach provides extensive**
**microanatomic data as a reference system for studies**
**of human auditory function.** © 2001 Academic Press
**_Key Words: human cerebral cortex; auditory cortex;_**
**cytoarchitecture; image analysis; brain mapping.**

**INTRODUCTION**

Topography and size of human primary auditory cortex (PAC) vary between the classical cytoarchitectonic
parcellations as well as between individual brains
(Brodmann, 1909; von Economo and Koskinas, 1925;
von Economo and Horn, 1930; Braak, 1980; Galaburda

1 To whom correspondence and reprint requests should be addressed at the Department of Neurology, Heinrich-Heine-University,
Moorenstrasse 5, 40225 Du¨sseldorf, Germany. Fax: �49-2118112336. E-mail: j.rademacher@fz-juelich.de.


and Sanides, 1980; Rademacher et al., 1993; Rivier and
Clarke, 1997; Clarke and Rivier, 1998). It is not known
to which degree divergent measures of auditory functions reflect either anatomic variability or individual
differences in cognitive processes. To date, knowledge
about the precise degree of biological variability in
shape, extent, and localization of borders has been
quite limited, because time-consuming cytoarchitectonic analysis has typically been restricted to only a
single or too few brains. The Brodmann map provides a
schematic concept of temporal lobe architecture and of
area 41, which represents PAC in mammalian brains
(Brodmann, 1909). Individual variations in the course
of the major brain gyri and sulci have not been considered (Eberstaller, 1890; Cunningham, 1892; Ono et al.,
1990). Unfortunately, high-resolution MR imaging
does not allow in vivo detection of the cytoarchitectonic
features of PAC.
The authors of the classical anatomical brain maps
assume a lack of variability in the entire population,
including interhemispheric symmetry and interindividual equality. However, today we are aware of the
fact that there can be considerable anatomic variability
in the position, size, and shape of cortical structures.
The gyral pattern especially of the superior temporal
region which contains the auditory cortex is highly
variable. Up to five transverse gyri (Campain and
Minckler, 1976) and marked interhemispheric asymmetries (Geschwind and Levitsky, 1968; Penhune et
_al., 1996; Pfeifer, 1920; von Economo and Horn, 1930)_
have been described. In an earlier cytoarchitectonic
study by one of the authors, Brodmann area 41 was
found to be larger on the left side in 6 of 10 brains
(Rademacher et al., 1993). Furthermore, the issue of
how architectonic field borders relate to primary or
secondary brain sulci is frequently neglected in both
structural and functional neuroimaging studies of
PAC. It has been hypothesized that the folding occurs
at the border between two architectonically distinct
cortical areas (Sanides, 1962). Hence, the location of
the transverse temporal sulci (Leonard et al., 1998)


-----

areas.
The interest in mapping cerebral gyri and sulci
stems from issues of functional localization. In vivo
human cognitive neuroanatomy is based on the identification of the anatomical substrate of human behavioral variation (Rademacher et al., 1992). In this context, planum temporale asymmetry has motivated
many observers to study the auditory cortex, taking
Heschl’s gyrus (HG) and the planum as its macroanatomic markers. Duplications of HG are increased in
families with learning disabilities (Leonard et al.,
1993) and planum temporale patterns are related to
handedness, absolute pitch, and musical ability (Witelson and Kigar, 1988; Steinmetz et al., 1991; Schlaug et
_al., 1995). Thus, the sizes of HG and the planum tem-_
porale have been interpreted as indicators of the efficiency and complexity of auditory and language processing. Although it has become conventional to refer
to HG as the site of PAC and to the planum temporale
as the site of auditory association cortex, one may
challenge the concept of tight associations between
micro- and macroanatomic parcellations. The finding
of striking variations in the sulcal landmarks of HG
has demonstrated that anatomic variability poses serious obstacles to the attempt to map behavioral function onto the brain (Leonard et al., 1998).
Given the lack of information on architectonic variability, most observers using functional imaging of auditory processing (Romani et al., 1982; Lauter et al.,
1985; Pantev et al., 1988, 1990; Liegeois-Chauvel et al.,
1991) relate their findings to a standardized coordinate
system (Talairach and Tournoux, 1988) or to gross
morphological landmarks such as HG (Penhune et al.,
1996). However, variability of temporal lobe anatomy
may represent important pitfalls to these approaches
(Steinmetz et al., 1990a; Rademacher et al., 1993), and
discrepancies between functional maps may be related
to the variability in size and geometry of the temporal
cortex. These limitations may explain in part why
there is still a debate about the localization and asymmetries of human auditory responses (Hashimoto et
_al., 1995; Ohtomo et al., 1998; Zouridakis et al., 1998)._
Clarification requires an overlay of cytoarchitectonic
areas with functionally defined areas in a common
reference system. The problem of individual variability
adds a distortion correction requirement that can be
implemented by the use of a three-dimensional (3-D)
probabilistic mapping strategy which is based on an
anatomical atlas system (Roland et al., 1994; Mazziotta
_et al., 1995; Zilles et al., 1995). Its usefulness has been_
demonstrated recently for the motor (Geyer et al.,
1996), somatosensory (Geyer et al., 1999), and visual
cortex (Amunts et al., 2000) as well as for Broca’s area
(Amunts et al., 1999). These studies described individual volume differences of distinct cytoarchitectonic ar

auditory response generation at a certain point in PAC,
we have to know not only the local status of neuronal
response characteristics, but also the relationship between them and the spatial extent of PAC. Similarily,
if we wish to facilitate the development of a sound basis
for in vivo cognitive neuroanatomy, we need to know
more about the homologies of MR visible macroanatomic markers across individual hemispheres and
brains. For the auditory cortex, improved mapping
strategies and more architectonic data are needed to
accommodate for structural variability. In our companion article (P. Morosan et al.), we describe the application of a recently developed cytoarchitectonic mapping
technique which is based on quantitative gray level
index (GLI) measures and an in vivo 3-D reference
brain. PAC (i.e., Te1) has been found to consist of three
cytoarchitectonic areas (Te1.1, Te1.0, Te1.2) along the
mediolateral axis of Brodmann area 41. For the
present cytoarchitectonic study, which is the largest
ever performed on the auditory cortex, we analyzed the
precise topographical patterns of area Te1 (i.e., total
PAC) in 27 human postmortem brains. The goals of the
present study were (i) the description of the range/
variability of anatomical phenotypes regarding the
shape, size, and extent of area Te1 bilaterally; (ii) the
analysis of the relationship between sulcal landmarks
and architectonic borders; and (iii) the 3-D reconstruction and mapping of area Te1 to a standard brain in
order to compare our data with the results of previous
anatomical or functional studies.

**MATERIALS AND METHODS**

**Subjects**

Twenty-seven adult human postmortem brains were
obtained from the body donor program of the Anatomical Institute of the University of Du¨sseldorf in accordance with the legal requirements. None of the subjects had a history of neurological or psychiatric
disease. The subjects consisted of 14 females and 13
males ages 37 to 85 years. None of the brains was
included in a previous study which was performed by
one of the authors (Rademacher et al., 1993). Handedness of the subjects was unknown, but it can be assumed that—similar to the incidence of the general
population—approximately 90% of our cases will have
been right-handed (Gilbert and Wysocki, 1992).

**Identification of Major Landmarks**

A reliable definition of the primary gyri and sulci
(frequency 100%; Ono et al., 1990) on the superior
temporal plane is mandatory for brain mapping studies of human auditory cortex. Figure 1 shows the mac

-----

**FIG. 1.** Anatomic definition of Heschl’s gyrus (HG). The exposed
surface of the superior temporal plane shows the oblique course of
HG bilaterally (view from above; anterior is at the top). HG is located
between the planum polare (PP) and the planum temporale (PT). As
shown for the left hemisphere, the anteromedial border of HG is
defined by the first transverse sulcus (FTS) and its posterior border
is defined by Heschl’s sulcus (HS). On the left side the reconstructed
map of cytoarchitectonic area Te1 is visualized (hatching occupying
HG). In our example, the right-sided superior temporal plane shows
two transverse gyri. This indicates that the definition of HG by
macroanatomic criteria alone may remain equivocal.

fissure, HG is the rostralmost transverse gyrus and
can be identified by its prominent size and characteristic shape (Steinmetz et al., 1989). Its oblique course
extends from the retroinsular region medially to the
rim of the first temporal gyrus laterally. Heschl’s sulcus is located between HG anteriorly and the planum
temporale posteriorly. Additional transverse gyri may
cover the planum temporale (Fig. 1, right hemisphere).
The first transverse sulcus is located between the planum polare anteriorly and HG posteriorly. Additional
transverse gyri on the planum polare have not been
described. The intermediate transverse sulcus, present
in up to 50% of hemispheres (Leonard et al., 1998),
indents HG along its long axis and subdivides it—
completely or incompletely—into anterior and posterior portions termed “duplications” (Penhune et al.,
1996). The topographical variations of gyri and sulci
and the total number of transverse gyri on the superior
temporal surface in each hemisphere were determined.

**MR Imaging and Histological Processing**
**of Postmortem Brains**

All 27 postmortem brains were fixed in 4% formalin
or in Bodian’s solution with a postmortem delay between 8 and 24 h. Ten of 27 brains were studied with
MR imaging prior to histological processing as described in the companion article (P. Morosan et al.). In
brief, the immersion-fixed brains were scanned (Siemens Magnetom 1.5 T) in a water-filled vacuum globe
in order to reduce image distortions by trapped air
bubbles. The applied 3-D FLASH fast gradient echo
sequence had a resulting voxel size of 1 � 1 � 1.17 mm,


series of alcohol, embedded in paraffin, and serially
sectioned (20-�m-thick sections). Every 15th section
was silver stained for cell bodies (Merker, 1983) and
every 60th section was used for quantitative volumetric analysis and 3-D reconstruction of area Te1. Ten
brains were analyzed in whole brain coronal serial
sections and 17 brains were analyzed in blocks cut
perpendicular to the main axis of HG thereby avoiding
cutting artifacts caused by oblique sections.

**Cytoarchitectonic Analysis**

The cytoarchitecture of every 60th section of the
paraffin-embedded brains was analyzed under low
magnification through a stereomicroscope guided by
the criteria neuronal packing density, cell size, arrangement, and staining intensity as described in the
companion article (P. Morosan et al.). Area Te1 (i.e.,
Brodmann area 41) was recognized in all 54 hemispheres by its general parvocellularity, the high packing density of neurons, and the prominent width of
layer IV (Rademacher et al., 1993). It represents the
auditory koniocortex including areas Te1.2, Te1.0, and
Te1.1, surrounded by less granular auditory parakoniocortex (Galaburda and Sanides, 1980). The borders
and surface extent of area Te1 were mapped to the
glass-covered sections onto their individual sulcal patterns in all 54 hemispheres. These borders were validated in 20 hemispheres by automated GLI measurements as described in the companion article (P.
Morosan et al.) and, more extensively, by Schleicher et
_al. (1999). The observer-independent areal borders of_
area Te1, defined by significant changes in the shape of
the GLI curves, were in good agreement with the areal
borders as defined by visual inspection and standard
cytoarchitectonic analysis. This finding was taken as a
proof of the reliability of the classical approach for PAC
border definition by visual inspection. We have analyzed total PAC—and not its subparcellations—in order to provide data that can be related to previous
structural and functional studies. Further parcellation
of PAC has led to a variety of maps by different authors
in which homologies of putative architectonic areas are
difficult to ascertain (von Economo and Koskinas,
1925; von Economo and Horn, 1930; Hopf, 1954; Braak,
1980; Galaburda and Sanides, 1980; Rivier and Clarke,
1997; Clarke and Rivier, 1998).

**Mapping Strategies**

_Individual Maps of Area Te1_

Since gyral and sulcal landmarks are reliably visualized with in vivo MR imaging, it is relevant to studies
of brain–behavior relationships to relate architectonic
findings to macroanatomic landmarks. In this context,


-----

(von Economo and Horn, 1930; Braak, 1980; Galaburda
and Sanides, 1980; Rademacher et al., 1993; Rivier and
Clarke, 1997; Clarke and Rivier, 1998). In the present
study, the location of area Te1 in each hemisphere of
the total series of 54 hemispheres was mapped to surface and coronal views of the respective individual
supratemporal plane. The surface views were based on
photographs of the intact and exposed supratemporal
plane after section of the frontoparietal operculum.
The visible sulcal landmarks were used for a proportional mapping of cytoarchitectonic area Te1 onto the
transverse gyri. Slice thickness, distance from slice to
slice, and linear shrinkage factors were used as parameters for creating a proportional enlargement of the
shrunken area onto the photograph of the normal-sized
brain. We refrained from providing a metric for the
maps, because the classic 2-D line drawings of 3-D
surface topography cannot be a true representation of
the real distances.

_Probabilistic Maps of Area Te1_

In 20 hemispheres of the series, area Te1 was
mapped to a computerized brain atlas, which is represented by an in vivo-acquired 3-D MR data set of an
individual brain. The procedure has already been described in detail elsewhere (Roland et al., 1994; Zilles et
_al., 1995; Amunts et al., 1999, 2000; Geyer et al., 1999)._
Mapping of the labeled volumes of area Te1 onto the
reference brain results in a 3-D map of the probability
that area Te1 will be found at a given voxel location in
stereotaxic space. For this purpose, all coronal histological sections of each brain were digitized (KS400,
Zeiss), then matched to the corresponding 3-D MR
volume, and ultimately warped to the computerized
reference brain by means of an affine matching procedure (i.e., rotation, translation, scaling) (Schormann et
_al., 1997; Schormann and Zilles, 1998). Hence, area_
Te1 maintained its individual shape, and interhemispheric topographical asymmetries could be analyzed.
Consecutively, we generated an atlas-based 3-D probability map representing location and extent of area
Te1 in 10 left and 10 right hemispheres. Probabilistic
contour maps can then be used to localize a region of
interest within PAC for a given range of probability.

_Talairach Atlas_

The spatially normalized brains—and area Te1—
were transferred to the Talairach space (Talairach and
Tournoux, 1988) by a simple coordinate transformation
in order to relate our cytoarchitectonic findings to this
normative stereotaxic database and to earlier studies
of structure and function in the human auditory cortex.
The extent of area Te1 in the sagittal, coronal, and
horizontal planes was calculated in Talairach coordi

left hemisphere. The y axis defines the anterior–posterior direction, with positive values anterior to the orthogonal plane through the anterior commissure and
negative values posterior to this landmark. The z axis
is defined by the horizontal plane which passes
through anterior and posterior commissures (AC–PC
line), with positive values superior to it and negative
values inferior to it. The bounding box for area Te1
(i.e., maximal extent in the three standard Talairach
planes (Penhune et al., 1996)) was measured in each
brain and averaged across 10 brains. The results were
compared to those of other brain mapping studies. Interhemispheric comparisons for minimum and maximum x, y, and z values of Te1 were performed as well
using paired t tests for dependent samples (Bonferroni
corrected).

**Measurements of Area Te1 and HG**

On every 60th histological section the extent of area
Te1 and HG (mm2) was measured separately for each
hemisphere with an electronic planimeter. The individual volumes of area Te1 and HG (mm3) were calculated
by adding the single slice measurements multiplied by
slice thickness and distance. The borders of HG used
were: (i) the depth of the first transverse sulcus anteromedially, (ii) the depth of Heschl’s sulcus posteriorly,
and (iii) the lateral hemispheric margin laterally
(Rademacher et al., 1992). The intermediate sulcus
was not taken as a border because of its inconsistency
(Ono et al., 1990; Leonard et al., 1998). When two or
more transverse gyri originated separately from the
retroinsular region, only the most anterior gyrus was
taken as HG, regardless of side (Steinmetz et al., 1989).
In order to correct our measurements for individual
brain shrinkage during histological processing, we calculated a mean shrinkage factor from 10 brains

[shrinkage factor (sf) � histological brain volume/fresh
brain volume; mean sf � 0.496]. Volumetric data which
represent the true in vivo size of HG and PAC were
then generated from the histological measures according to the formula: fresh volume � histological volume
x 1/shrinkage factor. For a better understanding of the
relative size of PAC, we also calculated proportional
dimensionless values (PAC/HG) from the data. Interhemispheric asymmetry of area Te1 (and HG) was
defined as any side difference which is larger than 10%
and its degree was determined as the coefficient
�Te1 � (VR � _VL)/(0.5(VR �_ _VL)), which corrects for_
total (R, right and L, left) Te1 size (V, volume) (Galaburda et al., 1987; Rademacher et al., 1993). Negative
values of �Te1 indicate leftward asymmetries and positive values indicate rightward asymmetries. The volumes of area Te1 and HG were compared between
hemispheres and sexes (two-way ANOVA with re

-----

**FIG. 2.** Topography of area Te1. Drawings from photographs of the superior temporal plane showing reconstructed maps of area Te1
(hatching occupying varying proportions of Heschl’s gyrus) in six left and right hemispheres representative of our sample (view from above;
anterior is at the top, the temporal pole is not shown, left is on the left, numbers represent brain codes). Coronal cuts from the same brains
are shown in Fig. 3 (see cross reference marks in Figs. 2F and 3F).


umes of both regions of interest were calculated by
averaging individual volumes. For the analysis of the
association between HG volumes and Te1 volumes,
Pearson correlation coefficients were calculated. Left–
right comparisons of volumes were performed by a
paired (left vs right hemisphere) t test (�� 0.05).

**RESULTS**

**Gyral and Sulcal Variations**

Variations in the number of transverse gyri included
a single transverse gyrus in 38 of 54 hemispheres
(70%), two transverse gyri in 13 of 54 hemispheres
(24%), and three transverse gyri in 3 of 54 hemispheres
(6%). The first transverse sulcus and Heschl’s sulcus
were found in all hemispheres. An intermediate transverse sulcus was present in 22 of 54 hemispheres


number of gyri or sulci. Examples of geometric variations of gyri and sulci are depicted in Figs. 2 and 3.

**Mapping Strategies**

_Individual Maps of Area Te1_

Cytoarchitectonic criteria, established for the preceding companion study of 20 hemispheres, also proved
valid for the whole series of 54 hemispheres. In each
case, the largest portion of area Te1 was localized on
HG. At the medial (retroinsular) origin of HG, a narrow strip of cortex contained hypocellular prokoniocortex with dominating infragranular layers. Laterally
and on the adjacent superior temporal plane, belt areas
of auditory association cortices could be distinguished
(Galaburda and Sanides, 1980). Individual cytoarchitectonic maps showing the surface topography of area
Te1 bilaterally are depicted in Fig. 2 (dorsal view; n �


-----

**FIG. 3.** Topography of area Te1. Camera lucida drawings of six representative coronal cuts taken from different levels of the superior
temporal plane showing area Te1 (hatching) in six left and right hemispheres (from the same brains as in Fig. 2, see cross reference marks
in Figs. 2F and 3F). The view is from anterior; caudal is at the top, left is on the left, and numbers represent the individual brain codes.


area Te1 does not extend to the lateral brain convexity
but portions of area Te1 may reach the planum polare
or planum temporale to varying degrees. There are no
sulcal landmarks for the medial (prokoniocortex) and
lateral (association cortex) borders of area Te1. The
lateral flattening of HG is not a reliable macroanatomic sign to detect the field boundary. Anteriorly, the
first temporal transverse sulcus represents only an
approximate landmark for the border of area Te1
which does not coincide with this sulcus along its total
mediolateral extent (Figs. 2 and 3). Similarily, Heschl’s
sulcus may be taken as the approximate posterior border of area Te1, but here again the overlap is far from
perfect. In addition, there is great variability among
the inconsistent secondary sulci. The intermediate
transverse sulcus, present in less than half of our sample, represents an approximate posterior border of area
Te1 in 14 hemispheres (64%) (for example, Fig. 2A)
while it does not do so in 8 hemispheres (36%) (for
example, Fig. 2B). Smaller tertiary sulci complicate the
cortical surface patterns and do not follow consistent


curved pattern of area Te1 in Fig. 2C (right side) and
the unusual topography of HG and area Te1 in Fig. 2F.
The representations of area Te1 in the coronal plane
provide further details about the relationship between
the course of the sulci and the localization of areal
borders (Fig. 3). The cytoarchitectonic borders may be
located in a sulcal fundus or they may be found on one
or the other wall of two neighboring gyri. In general,
right-sided area Te1 does not appear to be the mirror
image of (contralateral) left-sided area Te1.

_Probabilistic Maps of Area Te1_

Figure 4 presents color-coded maps of area Te1 for
the regions of identical probability in standardized
space from 10% (dark blue) to 100% (dark red) in steps
of 10%. Three standard planes are depicted (coronal,
axial, and sagittal planes) with cross-reference marks
superimposed to visualize the principle and utility of
multiple (orthogonal) views in the computerized 3-D
reference system. The axial plane shows that the loca

-----

**FIG. 4.** Probability maps of area Te1. As an example, coronal, axial,
and sagittal slices through the computerized reference brain (MR images) are shown (x, y, and z values are Talairach planes). Cross-reference marks are visualized to indicate the multiple (orthogonal) views.
The probability maps of cytoarchitectonically defined area Te1 from 10
brains have been superimposed. Color code: increasing probabilities
from dark blue (10% overlap) to dark red (100% overlap).

compared to its homologue on the left side. The axial
plane also indicates that area Te1 is shifted laterally


variability does not differ markedly between the hemispheres. In Fig. 5, the probability maps for 10 horizontal slices are overlaid on a grid in standardized space at
2-mm intervals. These maps can be used as an atlas to
localize area Te1 for a given range of probability. For
example, a significant focus of activation in a patient
with acoustic hallucinations was observed in the left
hemisphere at x � 47, y ��15, and z � 12 (Dierks et
_al., 1999); it would be found in the z �_ 12 map of area
Te1 within the 60% probability range.
In the present study, significant side differences
were observed for the location of area Te1 in the sagittal and coronal planes (Table 1). Compared to the left
side, right-sided area Te1 is shifted more than 5 mm
laterally. In the coronal plane, the right-sided rostral
and caudal borders of area Te1 are shifted �7 mm
anteriorly. The centroids of area Te1 (n � 10 brains)
show the largest side differences in the coronal plane
(left side, x ��42, y ��21, z ��7; right side, x �
�46, y ��13, z ��8). Maximum individual asymmetries (i.e., the maximum difference between any pair of
hemispheres) ranged from 9 mm in the sagittal and
axial planes to 13 mm in the coronal plane.

_Talairach Atlas_

Linear scaling and transformation of area Te1 to the
standard brain permits direct comparison of our architectonic data with the Talairach atlas and the results
from other studies. The maximal areal extent in stereotaxic space was outlined separately for both sides by
defining the bounding box which contains the total
volume of area Te1 from 10 brains. The resulting x, y,
and z coordinates define the maximal topographic variability of area Te1. The average location of PAC as
defined by cytoarchitectonic area Te1 differs in all dimensions from the location of PAC as defined in the
Talairach atlas (Table 1). In the x dimension, the lateral border is shifted medially by �4 mm (right side) to
�10 mm (left side). The medial border is shifted laterally by �3 mm on the right side and medially by �2
mm on the left side. The anterior border (y dimension)
of the right PAC, which was assumed to be the mirror
equivalent of the left PAC by Talairach and Tournoux
(1988), is shifted rostrally by �7 mm. Also the posterior border is shifted rostrally, by �11 mm on the right
and �4 mm on the left side. In the axial plane (z
dimension), the inferior borders are shifted ventrally
by �4 mm (right side) to �6 mm (left side). The maximum differences between the stereotaxic coordinates
of area Te1 in individual hemispheres and HG in the
Talairach atlas (i.e., the highest degree of mismatch)
were 16 mm in the sagittal plane, 18 mm in the coronal
plane, and 14 mm in the axial plane. To facilitate
comparison, we used the same Talairach coordinates


-----

**FIG. 5.** Atlas of area Te1. Probability maps of area Te1 at 10% steps in 10 horizontal slices overlaid on a grid in standardized space (z
separation � 2 mm; range, z � 0–16). In all slices, the outer contour (dark blue) represents 10% overlap. Grid scale in mm (1:2); x coordinates
labeled horizontally, y coordinates labeled vertically. The left hemisphere is on the left side. (A) Horizontal slices from z ��2 to �6. (B)
Horizontal slices from z ��8 to �16.


It is important to note, however, that the Talairach
atlas provides only crude information about the extent
of Brodmann area 41 and that the extent of HG as
visualized in the atlas is smaller (x � 29 to 55, y ��16
to �35, z � 8 to 16) than assumed by Penhune and
co-workers.
The average location of PAC as defined by cytoarchitectonic area Te1 also differs from the average location
of PAC as defined by HG in the study of Penhune et al.


resolution data from that study. The largest difference
was found for the lateral borders of PAC. It is shifted
medially by �10 mm on the left side and �6 mm on the
right side. The medial border is shifted medially by �2
(right) to �5 mm (left). The anterior border of PAC is
shifted rostrally by �1 (left) to �3 mm (right) and the
posterior border is shifted caudally by �2 mm (left side
only). In the axial plane, there is an �3-mm ventral
shift of superior and inferior borders on the left side


-----

Mean Values for Minimum and Maximum x, y, and z Values of Primary Auditory Cortex
in Stereotaxic Coordinates of the Talairach Atlas

_x dimension_ _y dimension_ _z dimension_
(sagittal plane) (coronal plane) (axial plane)

Authors Side Min Max Min Max Min Max

Present study[1] Left �26.9 � 2.1[a] 50.8 � 3.5[a] �34.5 � 3.2[a] �3.6 � 4.3[a] �1.9 � 4.0 14.7 � 2.1
Right 32.3 � 1.9[a] 56.7 � 3.1[a] �27.9 � 3.8[a] 3.2 � 5.3[a] �0.1 � 3.8 16.0 � 2.1
Penhune et al. (1996)[2] Left �31.5 � 2.2[a] 60.4 � 4.2 �32.8 � 3.2[a] �4.7 � 5.2[a] 1.1 � 2.8 17.7 � 2.3[a]

Right 34.0 � 2.8[a] 62.4 � 4.5 �28.7 � 3.4[a] 0.1 � 5.8[a] 0.3 � 4.1 16.0 � 2.8[a]

Talairach and Tournoux (1988)[2] Left �29 �61 �35 �8 4 16
Right 29 61 �35 �8 4 16

_Note. 1, cytoarchitectonic area Tel 1; 2, Heschl’s gyrus. In the x dimension statistical analysis was performed on absolute min/max values._
_a Significant difference (_ _p �_ 0.05) between the hemispheres.


taxic coordinates of area Te1 in individual hemispheres
and the spatial location of HG in the study of Penhune
_et al. (1996) are �15 mm in the sagittal plane, �10 mm_
in the coronal plane, and �11 mm in the axial plane. In
these cases, area Te1 was located more medially, more
rostrally, and more ventrally than HG.


**Measurements of Area Te1 and HG**

Table 2 shows the individual volumes, means, and
standard deviations of left (n � 27) and right (n � 27)
areas Te1 and HG. The respective volumes vary within
a wide range both interhemispherically and interindi

**TABLE 2**

Left and Right Volumes and Asymmetry Coefficients of Area Te1 and Heschl’s Gyrus

Area Te1 volume (mm[3]) Heschl gyrus volume (mm[3])

Brain Left Right �Te1 Left Right �HG

1 1721 2132 0.21 R 3198 3432 0.07 S
2 1662 2178 0.27 R 2369 2978 0.23 R
3 1313 1399 0.06 S 2718 3067 0.12 R
4 2092 828 �0.87 L 4811 4176 �0.14 L
5 1577 1242 �0.24 L 4067 2414 �0.51 L
6 1086 1147 0.05 S 2942 3155 0.07 S
7 830 1071 0.25 R 4915 3090 �0.46 L
8 2681 2173 �0.21 L 3392 3473 0.02 S
9 1198 926 �0.26 L 3034 3198 0.05 S
10 2440 1488 �0.48 L 4409 2525 �0.54 L
11 1327 1803 0.30 R 4732 5212 0.10 S
12 1140 599 �0.62 L 7217 1924 �1.16 L
13 1709 1845 0.08 S 2105 2224 0.05 S
14 1564 1224 �0.24 L 2026 1686 �0.18 L
15 1412 960 �0.38 L 2726 2747 0.01 S
16 1559 787 �0.66 L 2236 1429 �0.44 L
17 1665 1630 �0.02 S 2371 2125 �0.11 L
18 1698 1757 0.03 S 2742 2416 �0.13 L
19 1252 1351 0.08 S 3302 2218 �0.39 L
20 1069 1386 0.26 R 2703 3574 0.28 R
21 1525 2059 0.30 R 4183 3465 �0.19 L
22 2797 2366 �0.17 L 3762 3020 �0.22 L
23 2485 1678 �0.39 L 3742 5282 0.34 R
24 1292 1421 0.09 S 1965 2534 0.25 R
25 2336 2510 0.07 S 2529 3010 0.17 R
26 1500 2787 0.60 R 2579 4415 0.53 R
27 2520 1926 �0.27 L 5311 3896 �0.31 L
Mean 1683 1581 �0.08 3411 3062 �0.09
SD 538 564 0.34 1231 956 0.35


-----

(regions: area Te1, HG) showed a significant effect of
region (F(1,25) � 76.2; P � 0.0001) that was unrelated
to the sex of the subject (F(1,25 ) � 0.25; P � 0.5). In
each hemisphere, the individual volumes of HG were
larger than the ipsilateral volumes of area Te1 (Table
2). The relative size of area Te1, expressed as a proportion of the total individual volume of ipsilateral HG,
ranges from 16 to 92% (mean, 54%). On the left side it
varies between 16 and 92% (mean � SD; 54 � 20%)
and on the right side it varies between 20 and 83%
(mean � SD, 54 � 18%). The volume of area Te1 does
not correlate with the volume of HG.
The asymmetry indices �Te1 and �HG were calculated for each subject and the results are summarized
in Table 2. Leftward asymmetries result in negative
values, rightward asymmetries result in positive values. The individual asymmetry measures show no
clear pattern. A leftward asymmetry of area Te1 is
present in 12 of 27 brains (44%), while a rightward
asymmetry is present in 7 of 27 brains (26%). Eight
brains (30%) are symmetric for the size of area Te1.
Side differences of area Te1 and HG were not statistically significant.

**DISCUSSION**

The cytoarchitecture of human PAC has been studied since the beginning of the past century (Brodmann,
1909; von Economo and Koskinas, 1925; von Economo
and Horn, 1930). Advances in functional imaging of
auditory processing have promoted intensive microanatomic research in the past decade (Rademacher et
_al., 1993; Rivier and Clarke, 1997; Clarke and Rivier,_
1998). While modern imaging techniques have further
increased our understanding of the functional organization of auditory cortex, they also set new standards
for precise and reliable anatomical maps as a prerequisite for the topographical interpretation of activation
clusters. Visualization is an essential element in data
analysis to answer the question whether a distinct
auditory activation is located within a specific architectonic area. Appropriate methods of presentation
should convey information about the correlation between MR visible landmarks and architectonic borders
as well as information about the characteristic spatial
extent of an architectonic area in the population. Our
results show how the first objective can be achieved by
individual landmark-based anatomical maps (Figs. 2
and 3) while the second objective requires mapping of
the individual data to a spatial reference system (Figs.
4 and 5). The use of quantitative volumetric techniques
complements our approach (Tables 1 and 2).
It is well known that Brodmann area 41 is located in
the depth of the Sylvian fissure, but its extent on HG
and the neighboring transverse gyri varies between


method used to define PAC. Compared to the pigmentarchitectonically defined granular core area that is reported exclusively on the medial half of HG (Braak,
1978), cytoarchitectonically defined PAC extends more
laterally and covers about two-thirds of HG (von
Economo and Koskinas, 1925). We applied established
and novel quantitative brain mapping strategies to the
cytoarchitectonic analysis of human PAC. Our results
demonstrate that there is considerable intra- and interindividual variability in the localization and extent
of human PAC. The location of area Te1 can be defined
by MR visible anatomic landmarks, but with striking
differences in the degree of confidence regarding its
borders. Area Te1 always covers portions of HG and is
surrounded by belt areas of prokoniocortex or auditory
association cortex (Galaburda and Sanides, 1980;
Rademacher et al., 1993). However, there is no consistent and reliable association between gyri and sulci
and cytoarchitectonic borders. The precise location and
absolute size of area Te1 cannot be reliably inferred
from the macroanatomic landmarks. HG may serve
only as a structural marker of the location of PAC.
Especially the mediolateral and anteroposterior extent
of area Te1 do not covary with macroanatomy. A similar lack of a precise correspondence between gyral and
sulcal landmarks and a distinct cytoarchitectonic area
has been reported for the medial occipital lobe and
Brodmann area 17, i.e., primary visual cortex (Amunts
_et al., 2000). It was concluded that it is not possible to_
make valid predictions about the location of cytoarchitectonic areas and especially their borders, based on
the macroscopic surface anatomy alone. We suggest
that sufficient insight into the range of topographical
variations depends on the (complementary) description
of individual cytoarchitectonic phenotypes and of population-based probability maps. Both methods have
limitations. Caution has to be urged when gyral variations are taken as MR visible indicators of individual
variation in physiology and behavior. However, anatomic variation as depicted in the probability maps
may reflect in part inadequacies of the transformation
procedure to compensate for all types of individual
variation that arise. Given that exact and precise measurements of architectonic parcellation cannot be made
in living subjects, we provide information about just
how much imprecision is involved when either macroanatomy or classical brain templates are used as a
surrogate for cytoarchitecture.
Description of the macroanatomic landmarks is further complicated by the irregular geometry of the temporal transverse gyri which were first studied systematically by Heschl (1878). In vivo MR studies report
striking intra- and interindividual gyral and sulcal
variations which may confound the analysis of structural and functional relationships (Penhune et al.,


-----

esis that a standard anatomical pattern exists for the
superior temporal plane with one transverse gyrus on
the left side and two transverse gyri on the right side
(Pfeifer, 1920). We identified a single transverse gyrus
in more than 80% of the hemispheres and did not find
consistent asymmetries. Consequently, the definition
of a “standard” asymmetric pattern does not seem to be
a useful anatomic convention to study how auditory
function maps onto the cerebral cortex.
Von Economo and Horn (1930) were the first to study
the association between microanatomically defined
PAC and the transverse gyri. In our present series,
variability of area Te1 was considerably higher than
expected from earlier studies (Rademacher et al.,
1993). Individual cytoarchitectonic maps representing
the standard mapping approach of cytoarchitectonic
studies (von Economo and Horn, 1930; Stensaas et al.,
1974; Galaburda et al., 1978; Galaburda and Sanides,
1980; Rademacher et al., 1993; Rajkowska and Goldman-Rakic, 1995) show striking interindividual and
interhemispheric differences in the topography of area
Te1 (Figs. 2 and 3). Area Te1 comprises between 16 and
92% of the cortical volume of HG (Table 2) with no
significant correlation between the respective volumes
of HG and area Te1. Thus, the extent of area Te1 is
grossly overestimated by any approach that interprets
HG as the structural equivalent of PAC. When the
volume of HG is taken as equal to the size of area Te1,
an error of more than 100% is introduced in 22 of 54
(41%) hemispheres (calculated from Table 2). This finding needs to be kept in mind when inferences about the
size of PAC are made on the basis of HG volumetry
(Penhune et al., 1996).
That a priori information about the microanatomic
topography is mandatory has recently been shown for
the neuromagnetic approach (Lu¨tkenho¨ner and Steinstra¨ter, 1998). On one hand, evidence was given that it
is possible to register location differences below 1 mm.
On the other hand, the application of different analysis
strategies gave rise to a “fogging” effect on the order of
several millimeters. Comparable uncertainty about the
true relationship between structure and function in the
auditory system may arise when frequency-related activation is dichotomized along the medial vs lateral
half of HG (Strainer et al., 1997). For example, interpretation of bilateral functional data from brains 2B
and 2E (Fig. 2) would have been confounded by the
striking asymmetries—in opposed directions—of area
Te1 in the mediolateral direction. It is evident that
anatomic variations of HG like in brain 2F (Fig. 2)
make it impossible to infer the extent of area Te1 from
the gyral pattern. However, even the presence of an
easily identifiable single HG allows for considerable
variations in the topography of area Te1. Only with a


alignment in matching procedures.
While individual cytoarchitectonic maps do not provide the parametric data for 3-D mapping procedures
with data sets from the same or other modalities, they
are advantageous in that they visualize the range of
individual variations of micro- and macroanatomy. In
contrast, averaged maps suffer from a “blurring” effect
in this regard and show only the gyral and sulcal
topography of the atlas brain (see Figs. 4 and 5).
Landmark-based anatomic interpretation of auditory activation is valid in those particular cases in
which area Te1 coincides with HG. In the majority of
brains, however, this can be expected to be considerably inaccurate. The zone of maximal overlap (Figs. 4
and 5; dark red, 100%) is small in all planes, indicating
high variability. In our brain mapping study, linear
alignment of postmortem hemispheres and area Te1 to
the standard reference brain reduced interindividual
variations in location and extent of area Te1 by reducing the variability in size and spatial position of the
brain (Schormann et al., 1997; Schormann and Zilles,
1998). Probabilistic maps have been generated (Figs. 4
and 5) and can be used to localize a region of interest
within PAC for a given range of probability. We have
shown that this atlas tool permits one to identify retrospectively significant primary auditory activation
foci from functional studies within a distinct probability range of area Te1. The probability maps also show
that we have to expect considerable variations in the
auditory region. The generation of 3-D stereotaxic data
sets has permitted us to integrate individual brains
and cytoarchitectonic areas into the Talairach coordinate system. Collecting such data for the auditory cortex may be clinically useful for the planning of surgery
in patients with intractable temporal lobe epilepsy.
The definition of secure borders for anterior temporal
lobectomies may be facilitated by the complementary
use of probability maps including cytoarchitectonic
data.
How closely did the probability map for area Te1
match the location of PAC as identified by the localization of HG in the stereotaxic reference frame of the
Talairach atlas? The average location of area Te1 in
the present study differs in all dimensions from the
location of PAC as defined by HG in previous studies
(Penhune et al., 1996; Talairach and Tournoux, 1988).
The most striking differences were observed in the
mediolateral and anterior–posterior directions. The
lateral border of area Te1 is bilaterally located more
medially. Right-sided area Te1, which was assumed to
be the mirror equivalent of the left-sided area Te1 by
Talairach and Tournoux (1988), is located more rostrally. In the axial plane, there were rather small shifts
of the superior and inferior borders. The highest degree
of mismatch between the stereotaxic coordinates of


-----

to 18 mm in the coronal plane. This is not surprising,
since the location of macroanatomically defined HG in
a single hemisphere (Talairach atlas) cannot sufficiently represent the range of intersubject and interhemispheric variability in the population. Topographical uncertainty on the order of centimeters is relevant,
because functional studies have indicated that distinct
auditory foci may be located only a few millimeters
apart. For example, the auditory peak N1m arises from
a source located about 5 mm posterior to the middlelatency peak Pam (Pantev et al., 1995).
In contrast to the large number of reports on macroanatomic (Geschwind and Levitsky, 1968; Witelson
and Pallie, 1973; Wada et al., 1975; Galaburda et al.,
1987; Steinmetz et al., 1989, 1990b; Ide et al., 1996)
and architectonic (von Economo and Horn, 1930;
Braak, 1978; Galaburda et al., 1978; Witelson et al.,
1995) asymmetries in the size of auditory association
cortex, such asymmetries have only rarely been studied in PAC (von Economo and Horn, 1930; Rademacher
_et al., 1993; Penhune et al., 1996; Leonard et al., 1998)._
In the present study, interhemispheric differences
were observed for the location of area Te1 in all dimensions (Table 1). Compared to the left side, right-sided
area Te1 is shifted more anterolaterally. Maximum
individual asymmetries (i.e., the maximum difference
between any pair of hemispheres) of more than 1 cm
reflect a topographical asymmetry of the living human
brain, because putative methodological factors which
may introduce anatomical deformation are generally
not expected to influence left–right differences.
Left–right differences in the position of area Te1
imply that there are interhemispheric differences in
the location of cortical neurons related to the same
auditory process. This asymmetry is relevant for the
anatomical interpretation of functional activation in
imaging studies. Thus, a task-dependent interhemispheric asymmetry in the center of activation does not
necessarily mean that there is a functional lateralization for a given computation involving PAC on one side
and association cortex contralaterally. By the same
token, identical activation foci may well have their
origin from different anatomic modules. Consequently,
incongruencies in task-dependent spatial activation
patterns may either result from differences in the functional strategy by activating specific but divergent anatomic modules or result from a variant in the bilateral
topographical orientation. In a recent functional MR
study, there was a lack of cortical activation to a pure
tone task in half of the subjects (Strainer et al., 1997).
In his commentary, Zatorre (1997) discussed the possibility of differential cognitive processes as a basis for
this variability and urged investigators to be cautious
in interpreting response differences, unless normative
information is available for all task parameters. Given


variability (Dierks et al., 1999), we suggest that it is
equally important to control for both functional stimulation parameters and variations in architectonic topography.
Recent MR volume measurements of macroanatomically defined PAC (i.e., combined volumes of HG gray
and white matter) revealed significant left � right
asymmetries (Penhune et al., 1996). However, segmentation of the volumes in cortical gray and white matter
revealed that these asymmetries related only to the
white and not the gray matter. In the same study,
Penhune et al. interpreted their finding of a leftward
asymmetry of the white matter beneath HG as a side
difference in the volume of cortical fibers that carry
information to and from PAC. They suggested that this
asymmetry may reflect greater left-sided myelination
which could allow faster conduction of nerve impulses
and that it may be related to asymmetry of the planum
temporale. On the basis of the present architectonic
study, we would hesitate to support these speculations
because up to 84% of HG are occupied by non-PAC
areas (calculated from Table 2). The individual patterns reflect varying proportions of connections to and
from primary as well as secondary auditory cortices.
Assuming a proportional fiber distribution, one may
speculate from our data that—as an average—approximately half of the fiber tracts connect to area Te1.
Appropriately designed microanatomic analysis of the
auditory radiation may help to define less arbitrary
markers of a functionally relevant white matter anatomy. The feasibility of a complementary characterization and spatial mapping of fiber tracts has recently
been demonstrated for the human optic radiation (Bu¨rgel et al., 1999).
Our volume measurements of cytoarchitectonically
defined PAC demonstrate that there are no significant
asymmetries in the size of area Te1. Nevertheless, with
a varying degree and direction of asymmetry, more
than twofold volume differences may occur between
the hemispheres of individual brains. Interhemispheric differences in the number of transverse gyri
were not associated with systematic side differences of
area Te1. The impressive degree of interhemispheric
and interindividual variability makes interpretation of
quantitative results from smaller studies difficult. The
variability in the volume of area Te1 as estimated by
the proportion of the 50% volume (i.e., 50% overlap in
the probability map) in relation to the mean volumes
(27 brains) is higher than that for Brodmann area 17
(area Te1, �60% vs area 17, �70%; lower values indicate higher variability) in a recent cytoarchitectonic
study from our laboratory (Amunts et al., 2000). The
variability of area 17 is considerably lower than the
variability for Brodmann area 18 (�40%) in the same
study. It may be speculated that the degree of struc

-----

than the association cortices.
Beyond the macroscopic view, quantitative measures
for area Te1 may also help to discuss models of auditory function. Much of our knowledge about the functional organization of the human auditory cortex comes
from magnetic source imaging (Romani et al., 1982;
Hari, 1990; Hashimoto et al., 1995; Lu¨tkenho¨ner and
Steinstra¨ter, 1998; Ohtomo et al., 1998; Pantev et al.,
1998; Salmelin et al., 1998, 1999). Mapping of the
sources of the auditory-evoked magnetic fields to the
anatomy of the superior temporal plane is of tremendous importance to these studies of brain–behavior
relationships. Dependening on which estimate is favored, it has been assumed that to produce the same
auditory dipole moment the cortical generator may
2
cover an area of 50 mm (model I (Lu¨tkenho¨ner and
2
Steinstra¨ter, 1998)) to 1500 mm (model II (Hari,
1990)). With the mean surface area of area Te1 in our
sample being �560 mm2, model II appears to overestimate the actual dimensions of PAC while model I
appears to propose more appropriate numbers.
In conclusion, our data predict that lack of understanding of intra- and interindividual variability of
size, shape, and location of area Te1 may lead to structural–functional mismatch of important components of
the auditory network. Since variations of both the sulcal pattern and the cytoarchitectonic borders of area
Te1 are not significantly correlated, PAC cannot be
reliably and precisely localized on high-resolution MR
images of the temporal lobe. The probability of localizing area Te1 is higher on the surface of HG compared
to the surface of the planum polare or temporale. However, the smaller the distance to the transverse sulci,
the greater the probability of finding non-PAC areas.
The results provide a rationale for thinking about individual variability and hemispheric asymmetry when
designing morphometric and functional studies. Mapping area Te1 to a 3-D human brain has provided a
stereotaxic atlas-based tool that can quantify the probability of localizing specific functional properties inside
or outside of PAC. The probability maps of a cytoarchitectonic area can be used to clarify the role of variations in both cortical structure and cognitive strategy.
We suggest that they represent a more valid approximation to a functionally relevant parcellation system
than a gyrus-based reference space.

**ACKNOWLEDGMENTS**

We are grateful to U. Blohm and C. Opfermann-Ru¨ngeler for their
excellent technical assistance. This work was supported by a grant
from the Deutsche Forschungsgemeinschaft (SFB 194/A6) and from


Amunts, K., Malikovic, A., Mohlberg, H., Schormann, T., and Zilles,
K. 2000. Brodmann’s areas 17 and 18 brought into stereotaxic
space—Where and how variable? NeuroImage 11: 66–84.
Amunts, K., Schleicher, A., Bu¨rgel, U., Mohlberg, H., Uylings,
H. B. M., and Zilles, K. 1999. Broca’s region revisited: Cytoarchitecture and intersubject variability. J. Comp. Neurol. 412: 319–
341.
Braak, H. 1978. On magnopyramidal temporal fields in the human
brain—Probable morphological counterparts of Wernicke’s sensory
speech region. Anat. Embryol. 152: 141–169.
Braak, H. 1980. Architectonics of the Human Telencephalic Cortex.
Springer-Verlag, Berlin.
Brodmann, K. 1909. Vergleichende Lokalisationslehre der Grosshirn_rinde. Barth, Leipzig._
Bu¨rgel, U., Schormann, T., Schleicher, A., and Zilles, K. 1999. Mapping of histologically identified long fiber tracts in human cerebral
hemispheres to the MRI volume of a reference brain: Position and
spatial variability of the optic radiation. NeuroImage 10: 489–499.
Campain, R., and Minckler, J. 1976. A note on the gross configurations of the human auditory cortex. Brain Lang. 3: 318–323.
Clarke, S., and Rivier, F. 1998. Compartments within human primary auditory cortex: Evidence from cytochrome oxidase and acetylcholinesterase staining. Eur. J. Neurosci. 10: 741–745.
Cunningham, D. J. 1892. Contribution to the Surface Anatomy of the
_Cerebral Hemispheres. Royal Irish Acad., Dublin._
Dierks, T., Linden, D. E. J., Jandl, M., Formisano, E., Goebel, R.,
Lanfermann, H., and Singer, W. 1999. Activation of Heschl’s gyrus
during auditory hallucinations. Neuron 22: 615–621.
Eberstaller, O. 1890. Das Stirnhirn. Ein Beitrag zur Anatomie der
_Oberfla¨che des Gehirns. Urban & Schwarzenberg, Vienna/Leipzig._
Galaburda, A., and Sanides, F. 1980. Cytoarchitectonic organization
of the human auditory cortex. J. Comp. Neurol. 190: 597–610.
Galaburda, A. M., Corsiglia, J., Rosen, G. D., and Sherman, G. F.
1987. Planum temporale asymmetry: Reappraisal since
Geschwind and Levitsky. Neuropsychologia 25: 853–868.
Galaburda, A. M., Sanides, F., and Geschwind, N. 1978. Human
brain. Cytoarchitectonic left–right asymmetries in the temporal
speech region. Arch. Neurol. 35: 812–817.
Geschwind, N., and Levitsky, W. 1968. Human brain: Left–right
asymmetries in temporal speech region. Science 161: 186–187.
Geyer, S., Ledberg, A., Schleicher, A., Kinomura, S., Schormann, T.,
Bu¨rgel, U., Klingberg, T., Larsson, J., Zilles, K., and Roland, P. E.
1996. Two different areas within the primary motor cortex of man.
_Nature 382: 805–807._
Geyer, S., Schleicher, A., and Zilles, K. 1999. Areas 3a, 3b, and 1 of
human primary somatosensory cortex. NeuroImage 10: 63–83.
Gilbert, A. N., and Wysocki, C. J. 1992. Hand preference and age in
United States. Neuropsychologia 30: 601–608.
Hari, R. 1990. The neuromagnetic method in the study of the human
auditory cortex. In Auditory Evoked Magnetic Fields and Electric
_Potentials. Advances in Audiology (F. Grandori, M. Hoke, and G._
Romani, Eds.). Karger, Basel.
Hashimoto, I., Mashiko, T., Yoshikawa, K., Mizuta, T., Imada, T.,
and Hayashi, M. 1995. Neuromagnetic measurements of the human primary auditory response. Electroencephalogr. Clin. Neuro_physiol. 96: 348–356._
Heschl, R. L. 1878. Ueber die Vordere Quere Schla¨fenwindung des
_Menschlichen Grosshirns. Wilhelm Braumu¨ller, Vienna._
Hopf, A. 1954. Die Myeloarchitektonik des Isocortex temporalis beim


-----

patterns in the human Sylvian fissure: Hemispheric and sex differences. Cereb. Cortex 6: 717–725.
Lauter, J. L., Herscovitch, P., Formby, C., and Raichle, M. E. 1985.
Tonotopic organization in human auditory cortex revealed by
positron emission tomography. Hear. Res. 20: 190–205.
Leonard, C., Voeller, K., Lombardino, L., Morris, M., Alexander, A.,
Andersen, H., Garofalakis, M., Hynd, G., Honeyman, J., Mao, J.,
Agee, O., and Staab, E. 1993. Anomalous cerebral structure in
dyslexia revealed with magnetic resonance imaging. Arch. Neurol.
**50: 461–469.**
Leonard, C. M., Puranik, C., Kuldau, J. M., and Lombardino, L. J.
1998. Normal variation in the frequency and location of human
auditory cortex landmarks. Heschl’s gyrus: Where is it? Cereb.
_Cortex 8: 397–406._
Liegeois-Chauvel, C., Musolino, A., and Chauvel, P. 1991. Localization of primary auditory area in man. Brain 107: 115–131.
Lu¨tkenho¨ner, B., and Steinstra¨ter, O. 1998. High-precision neuromagnetic study of the functional organization of the human auditory cortex. Audiol. Neurootol. 3: 191–213.
Mazziotta, J. C., Toga, A. W., Evans, A., Fox, P., and Lancaster, J.
1995. A probabilistic atlas of the human brain: Theory and rationale for its development. NeuroImage 2: 89–101.
Merker, B. 1983. Silver staining of cell bodies by means of physical
development. J. Neurosci. Methods 9: 235–241.
Ohtomo, S., Nakasato, N., Kanno, A., Hatanaka, K., Shirane, R.,
Mizoi, K., and Yoshimoto, T. 1998. Hemispheric asymmetry of the
auditory evoked N100m response in relation to the crossing point
between the central sulcus and Sylvian fissure. Electroencepha_logr. Clin. Neurophysiol. 108: 219–225._
Ono, M., Kubik, S., and Abernathey, C. D. 1990. Atlas of the Cerebral
_Sulci. Thieme, Stuttgart/New York._
Pantev, C., Bertrand, O., Eulitz, C., Verkindt, C., Hampson, S.,
Schuierer, G., and Elbert, T. 1995. Specific tonotopic organizations
of different areas of the human auditory cortex revealed by simultaneous magnetic and electric recordings. Electroencephalogr.
_Clin. Neurophysiol. 94: 26–40._
Pantev, C., Hoke, M., Lehnertz, K., Lu¨tkenho¨ner, B., Anogianakis,
G., and Wittkowski, W. 1988. Tonotopic organization of the human
auditory cortex revealed by transient auditory evoked magnetic
fields. Electroencephalogr. Clin. Neurophysiol. 69: 160–170.
Pantev, C., Hoke, M., Lehnertz, K., Lu¨tkenho¨ner, B., Fahrendorf, G.,
and Sto¨ber, U. 1990. Identification of sources of brain neuronal
activity with high spatiotemporal resolution through combination
of neuromagnetic source localization (NMSL) and magnetic resonance imaging (MRI). Electroencephalogr. Clin. Neurophysiol. 75:
173–184.
Pantev, C., Oostenveld, R., Engelien, A., Ross, B., Roberts, L. E., and
Hoke, M. 1998. Increased auditory cortical representation in musicians. Nature 392: 811–814.
Penhune, V. B., Zatorre, R. J., MacDonald, J. D., and Evans, A. C.
1996. Interhemispheric anatomical differences in human primary
auditory cortex: Probabilistic mapping and volume measurement
from magnetic resonance scans. Cereb. Cortex 6: 661–672.
Pfeifer, R. A. 1920. Myelogenetisch-anatomische Untersuchungen
u¨ber das kortikale Ende der Ho¨rleitung. Abh. Math. Phys. Kl.
_Sa¨chs. Akad. Wiss. 37: 1–54._
Rademacher, J., Caviness, V. S., Jr., Steinmetz, H., and Galaburda,
A. M. 1993. Topographical variation of the human primary cortices
and its relevance to brain mapping and neuroimaging studies.
_Cereb. Cortex 3: 313–329._
Rademacher, J., Galaburda, A. M., Kennedy, D. N., Filipek, P. A.,
and Caviness, V. S., Jr. 1992. Human cerebral cortex: Localization,
parcellation, and morphometry with magnetic resonance imaging.


definition of prefrontal areas in the normal human cortex. II.
Variability in locations of areas 9 and 46 and relationship to the
Talairach coordinate system. Cereb. Cortex 5: 323–337.
Rivier, F., and Clarke, S. 1997. Cytochrome oxidase, acetylcholinesterase, and NADPH-diaphorase staining in human supratemporal
and insular cortex: Evidence for multiple auditory areas. Neuro_Image 6: 288–304._
Roland, P. E., Graufelds, C. J., Wahlin, J., Ingelman, L., Andersson,
M., Ledberg, A., Pedersen, J., Akerman, S., Dabringhaus, A., and
Zilles, K. 1994. Human brain atlas: For high-resolution functional
and anatomical mapping. Hum. Brain Mapp. 1: 173–184.
Romani, G. L., Williamson, S. J., and Kaufman, L. 1982. Tonotopic
organization of the human auditory cortex. Science 216: 1339–
1340.
Salmelin, R., Schnitzler, A., Parkkonen, L., Biermann, K., Helenius,
P., Kiviniemi, K., Kuukka, K., Schmitz, F., and Freund, H. 1999.
Native language, gender, and functional organization of the auditory cortex. Proc. Natl. Acad. Sci. USA 96: 10460–10465.
Salmelin, R., Schnitzler, A., Schmitz, F., Ja¨ncke, L., Witte, O. W.,
and Freund, H.-J. 1998. Functional organization of the auditory
cortex is different in stutterers and fluent speakers. NeuroReport
**9: 2225–2229.**
Sanides, F. 1962. Die Architektonik des Menschlichen Stirnhirns.
Springer-Verlag, Berlin.
Schlaug, G., Ja¨ncke, L., Huang, Y., and Steinmetz, H. 1995. In vivo
evidence of structural brain asymmetry in musicians. Science 267:
699–701.
Schleicher, A., Amunts, K., Geyer, S., Simon, U., Zilles, K., and
Roland, P. E. 1999. Observer-independent method for microstructural parcellation of cerebral cortex: A quantitative approach to
cytoarchitectonics. NeuroImage 9: 165–177.
Schormann, T., Dabringhaus, A., and Zilles, K. 1997. Extension of
the principal axes theory for the determination of affine transformations. In Proceedings of the DAGM: Informatik-Aktuell, pp.
384–391. Springer-Verlag, Berlin.
Schormann, T., and Zilles, K. 1998. Three-dimensional linear and
nonlinear transformations: An integration of light microscopical
and MRI data. Hum. Brain Mapp. 6: 339–347.
Steinmetz, H., Fu¨rst, G., and Freund, H.-J. 1990a. Variation of
perisylvian and calcarine anatomic landmarks within stereotaxic
proportional coordinates. Am. J. Neuroradiol. 11: 1123–1130.
Steinmetz, H., Rademacher, J., Huang, Y., Hefter, H., Zilles, K.,
Thron, A., and Freund, H.-J. 1989. Cerebral asymmetry: MR
planimetry of the human planum temporale. J. Comput. Assist.
_Tomogr. 13: 996–1005._
Steinmetz, H., Rademacher, J., Ja¨ncke, L., Huang, Y., Thron, A., and
Zilles, K. 1990b. Total surface of temporoparietal intrasylvian
cortex: Diverging left–right asymmetries. Brain Lang. 39: 357–
372.
Steinmetz, H., Volkmann, J., Ja¨ncke, L., and Freund, H.-J. 1991.
Anatomical left–right asymmetry of language-related temporal
cortex is different in left- and right-handers. Ann. Neurol. 29:
315–319.
Stensaas, S. S., Eddington, D. K., and Dobelle, W. H. 1974. The
topography and variability of the primary visual cortex in man.
_J. Neurosurg. 40: 747–755._
Strainer, J. C., Ulmer, J. L., Yetkin, F. Z., Haughton, V. M., Daniels,
D. L., and Millen, S. J. 1997. Functional MR of the primary
auditory cortex: An analysis of pure tone activation and tone
discrimination. Am. J. Neuroradiol. 18: 601–610.
Talairach, J., and Tournoux, P. 1988. A Co-planar Stereotaxic Atlas


-----

Rindenarchitektonik der Supratemporalflache, ihre individuellen
und ihre Seitenunterschiede. Z. Neurol. Psychiat. 130: 678–757.
von Economo, C., and Koskinas, G. N. 1925. Die Cytoarchitektonik
_der Hirnrinde des Erwachsenen Menschen. Springer-Verlag, Ber-_
lin.
Wada, J. A., Clarke, R., and Hamm, A. 1975. Cerebral hemispheric
asymmetry in humans. Cortical speech zones in 100 adult and 100
infant brains. Arch. Neurol. 32: 239–246.
Witelson, S. F., Glezer, I. I., and Kigar, D. L. 1995. Women have
greater density of neurons in posterior temporal cortex. J. Neuro_sci. 15: 3418–3428._
Witelson, S. F., and Kigar, D. L. 1988. Asymmetry in brain function
follows asymmetry in anatomical form: Gross, microscopic, postmortem and imaging studies. In Handbook of Neuropsychology (F.


Elsevier, New York.
Witelson, S. F., and Pallie, W. 1973. Left hemisphere specialization
for language in the newborn. Neuroanatomical evidence of asymmetry. Brain 96: 641–646.
Zatorre, R. J. 1997. Functional neuroimaging in the study of the
human auditory cortex. Am. J. Neuroradiol. 18: 621–623.
Zilles, K., Schlaug, G., Matelli, M., Luppino, G., Schleicher, A., Qu¨,
M., Dabringhaus, A., Seitz, R., and Roland, P. E. 1995. Mapping of
human and macaque sensorimotor areas by integrating architectonic, transmitter receptor, MRI and PET data. J. Anat. 187:
515–537.
Zouridakis, G., Simos, P. G., and Papanicolaou, A. C. 1998. Multiple
bilaterally asymmetric cortical sources account for the auditory
N1m component. Brain Topogr. 10: 183–189.


-----

