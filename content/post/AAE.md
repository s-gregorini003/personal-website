---
title: "3D Printed Destructive Interference Acoustic Absorbers"
subtitle: "Design, Production and Evaluation"
date: 2020-06-10T08:45:42+01:00
draft: false 
---
<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

## Abstract

This blog post is to summarise a research project conducted at the beginning of 2019 as part of the Advanced Audio Engineering module (MSc Audio Engineering, Leeds Beckett University). The project discusses the potentials of achieving high performance in terms of sound absorption through additive manufacturing techniques.

The absorbers are designed to exploit the principle of passive destructive interference (PDI) and manufactured using a commercially available fused deposition modeling (FDM) 3D printer. The specimen are cylindrical and produced with cavities of different lengths. The absorption coefficient is evaluated using an impedance tube and following the specifications of the standard BS EN ISO 10534-2:2001.

The results show that significant sound absorption can be achieved, although some absorption peaks do not match the expected frequencies. This may be caused by turbulence and resonance phenomena, especially in samples with greater diameter of the cavity. Futher investigation is required, but the potential of these technologies in terms of efficiency over manufacturing cost and absorber size is undoubted.


## Introduction

The aim of the project is to design and manufacture Passive Destructive Interference (PDI) absorbers using Additive Manufacturing (AM) techniques and then to evaluate their performance through a low cost, self-built impedance tube. The main outcome of the measurement process is a set of diagrams of the normal absorption factor α of the specimens as a function of frequency in a mid-low spectrum range. As suggested by Godbold (2007) and Setaki (2015) the sound absorption curves will be then analyzed using two values:
- The frequency of peak sound absorption
- The half-power bandwidth of the peak

These values will be used to determine the effects of the tested geometries and to verify if the experimental results agree with the values expected from the samples in the design phase.
To achieve this, measurement equipment and samples must be designed and a measurement of α has to be done for each sample according to the methodology explained in Section 4.3.


## Theory and Methodology

According to the theory (Setaki, 2015, p. 5) the samples are designed to absorb specific frequencies through passive destructive interference. These frequencies depend mainly on the specimen's geometry, and can be calculated in advance through the following equation 
<div>$$f_n = {(2n-1)*c\over 2L}$$</div>

Where *L* (m) is the length of the cavity and *c* (m/s) is the speed of sound in the air.

{{< figure src="/img/aae/sample-A-specs.png" caption="Specification and design of a specimen." >}}



{{< figure src="/img/aae/TestEquipmentDiagram.png" caption="Measurement test equipment layout." >}}


{{< figure src="/img/aae/specimen.jpg" caption="Two specimen used for measurement." >}}

## Findings 


{{< figure src="/img/aae/sample-A-results.png" caption="Measured absorption coefficient for sample A compared to predicted peak frequencies." >}}

## References

- [Sound absorption and additive manufacturing](https://www.researchgate.net/publication/281005456_Sound_absorption_and_additive_manufacturing)



{{< figure src="/img/aae/PATH" caption="CAPTION" >}}
<div>$$TeX Code$$</div>

\( \alpha \)
test \( \alpha \)
