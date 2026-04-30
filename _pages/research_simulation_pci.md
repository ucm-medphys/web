---
title: "Research — Phase contrast simulation"
layout: researchlay
excerpt: "Monte Carlo simulation of grating-based X-ray phase contrast imaging with GAMOS and the SyRIS framework."
sitemap: false
permalink: /research/simulation/pci/
---

# Phase contrast simulation

**GAMOS-based Monte Carlo modelling of Talbot–Lau interferometry.**

Accurate simulation of grating-based phase contrast imaging systems is essential for system design, protocol optimisation, and the generation of synthetic data for our [virtual clinical trial]({{ site.url }}{{ site.baseurl }}/research/vct/) pipeline. We have integrated full phase contrast simulation capabilities into **GAMOS**, covering the Talbot–Lau interferometric geometry used in the [XTALIS]({{ site.url }}{{ site.baseurl }}/research/xtalis/) system.

---

### Simulation framework

Our implementation extends GAMOS with dedicated scorers and geometry modules for:

- **Grating modelling** — absorption, phase, and analyser gratings with configurable period and orientation
- **Phase stepping** — automatic acquisition of phase-stepping curves and extraction of the three contrast channels (absorption, differential phase, dark-field)
- **Polychromatic sources** — realistic X-ray spectra from micro-focus and clinical sources
- **Detector noise** — photon statistics and electronic noise models

This enables simulation of the complete interferometric acquisition chain under controlled conditions.

---

### Verification against experiment

We have systematically verified our simulation chain against experimental measurements on the XTALIS setup:

- Comparison of phase-stepping curve shape and visibility across the field of view
- Transmission and dark-field contrast in phantoms and ex vivo specimens
- Agreement between simulated and measured point spread functions

This cross-validation — reported in our [SyRIS verification paper](#publications) — establishes the quantitative fidelity of the simulated images.

---

### Applications

- **System optimisation** — grating period, inter-grating distances, source size, and spectrum for breast and chest imaging
- **Synthetic data** — generation of realistic phase contrast datasets for algorithm development and benchmarking
- **Dosimetry** — dose estimation for phase-stepping protocols vs. conventional absorption imaging
- **Artefact studies** — moiré and other interferometric artefacts (see also [Deep Learning]({{ site.url }}{{ site.baseurl }}/research/deep-learning/))

---

### Publications {#publications}

- *X-ray phase contrast imaging in GAMOS.* Sánchez-Lara V, Lozano FR, Huerga C, Martínez-Gómez LC, García Pinto D. [Physica Medica 142 (2026)](https://www.physicamedica.com/article/S1120-1797(26)00003-7/fulltext){:target="_blank"}
- *Verification of the SyRIS simulation framework for a Talbot–Lau interferometric phase contrast imaging system with a micro-focus X-ray source.* Sánchez-Lara A, García Pinto D, Chevalier del Río M. Physica Medica (2022)

---

*See also [XTALIS]({{ site.url }}{{ site.baseurl }}/research/xtalis/), [Monte Carlo simulation]({{ site.url }}{{ site.baseurl }}/research/simulation/), and the [publications page]({{ site.url }}{{ site.baseurl }}/publications/).*
