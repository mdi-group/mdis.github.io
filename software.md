---
layout: page
title: Software
description: Software developed or contributed to by MDIS
---

MDIS is involed in a number of open source software projects for the materials science 
community. We believe in the power of open software to enrich and improve science. We
try, wherever possible, to ensure that our computational work is accompinied by easy
to use software. This often requires some significant additional effort and at times
we have definitely cursed the decision to make software open and accessible, but the 
rewards have always been more than worth the effort. 

## SMACT

Semiconducting Materials by Analogy and Chemical Theory (SMACT) is a Python package
for high-throughput virtual screening for new functional materials. SMACT uses 
chemical heuristics to search through vast compositional spaces to identify target
functional materials. SMACT also has functionallity for deriving reasonable 
crystal structures for a given composition and can be used to interface with a range
of modern machine learning techniques and atomistic modelling packages.

**Code:**[https://github.com/WMD-group/SMACT](https://github.com/WMD-group/SMACT) 
**Docs:**[https://smact.readthedocs.io/en/latest/](https://smact.readthedocs.io/en/latest/)

```bash
pip install smact
```

#### SMACT in action

Some publications where SMACT has been used to discover new materials:

* [Computational Screening of All Stoichiometric Inorganic Materials](https://www.sciencedirect.com/science/article/pii/S2451929416301553)
* [Data-driven discovery of photoactive quaternary oxides using first-principles machine learning](https://pubs.acs.org/doi/abs/10.1021/acs.chemmater.9b01519)
* [Computer-aided design of metal chalcohalide semiconductors: from chemical composition to crystal structure](https://pubs.rsc.org/en/content/articlehtml/2018/sc/c7sc03961a)
* [Materials discovery by chemical analogy: role of oxidation states in structure prediction](https://pubs.rsc.org/en/content/articlehtml/2018/fd/c8fd00032h)

## MacroDensity

_MacroDensity_ is a Python package for analysing and manipulating electron densities and 
electrostatic potential maps obtained from modern electronic strucutre codes. The 
primary functionality of MacroDensity is to obtain energy band alignment diagrams for
extended solids, however it can also be used to explore and study potential maps for
any arbitrary property.

**Code:**[https://github.com/WMD-group/MacroDensity](https://github.com/WMD-group/MacroDensity)
**Docs:**[https://github.com/WMD-group/MacroDensity](https://github.com/WMD-group/MacroDensity)

```bash
pip install git+git://github.com/WMD-group/MacroDensity.git
```
#### MacroDensity in action

Some publications where MacroDensity has been used:

* [Electronic Chemical Potentials of Porous Metal–Organic Frameworks](https://pubs.acs.org/doi/full/10.1021/ja4110073)
* [Crystal electron binding energy and surface work function control of tin dioxide](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.89.115320)
* [Quasi-particle electronic band structure and alignment of the V-VI-VII semiconductors SbSI, SbSBr, and SbSeI for solar cells](https://aip.scitation.org/doi/abs/10.1063/1.4943973)
* [Interplay of Orbital and Relativistic Effects in Bismuth Oxyhalides: BiOF, BiOCl, BiOBr, and BiOI](https://pubs.acs.org/doi/full/10.1021/acs.chemmater.6b00349)
* [Band alignment of the hybrid halide perovskites CH<sub>3</sub>NH<sub>3</sub>PbCl<sub>3</sub>, CH<sub>3</sub>NH<sub>3</sub>PbBr<sub>3</sub> and CH<sub>3</sub>NH<sub>3</sub>PbI<sub>3</sub>](https://pubs.rsc.org/en/content/articlehtml/2015/mh/c4mh00174e)


## UnlockNN

_UnlockNN_ is a Python package which can be used to combine the expressive power of 
graph neural networks with the principled uncertainty quantification of Gaussian 
processes. UnlockNN was written by Alex Moriarty - currently at UCL - and uses
TensorFlow and TensorFlow Probability for an efficient implementation.

**Code:**[https://github.com/a-ws-m/unlockNN](https://github.com/a-ws-m/unlockNN)
**Docs:**[https://unlocknn.readthedocs.io/en/latest/](https://unlocknn.readthedocs.io/en/latest/)

```bash
pip install unlocknn
```
#### UnclockNN in action

Some publications where UnlockNN has been used:

* [Entropy-based active learning of graph neural network surrogate models for materials properties](https://aip.scitation.org/doi/abs/10.1063/5.0065694)

## SuperResTomo

_superres-tomo_ is a package of useful scripts and models for applying neural networks for tomographic reconstruction of X-ray images. The package also includes models and scripts useful for the analysis of the images generated, allowing tasks such as semantic segmentation of very large images and removing noise from low dose images.

**Code:** [https://github.com/keeeto/super_tomo_py](https://github.com/keeeto/super_tomo_py)
**Docs:** [https://superres-tomo.readthedocs.io/en/latest/about.html](https://superres-tomo.readthedocs.io/en/latest/about.html)
