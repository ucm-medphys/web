---
title: "Research — XTALIS"
layout: researchlay
excerpt: "XTALIS — grating-based phase contrast X-ray imaging system developed at UCM."
sitemap: false
permalink: /research/xtalis/
---

# XTALIS

**Grating-based phase contrast X-ray imaging.**

XTALIS is our home-built X-ray phase contrast imaging system, based on **Talbot–Lau grating interferometry** with a micro-focus laboratory X-ray source. The system has been developed entirely in-house and is the central experimental platform of our research line, providing data for validation studies, algorithm development, and preclinical imaging.

---

## Why phase contrast?

Conventional radiography exploits the absorption of X-rays in tissue, which provides limited contrast between soft tissues of similar density. **Phase contrast imaging** complements absorption by exploiting the refractive index of materials, giving access to two additional contrast channels:

- **Differential phase contrast** — sensitive to the gradient of the refractive index; reveals interfaces and structural details invisible to absorption.
- **Dark-field contrast** — sensitive to small-angle scattering; particularly valuable in lung imaging (alveolar microstructure) and in characterising microcalcifications and fibrous tissue in the breast.

This is especially relevant in mammography and lung imaging, where subtle soft-tissue differences are diagnostically decisive.

---

## The XTALIS system

XTALIS implements the **Talbot–Lau interferometer** geometry, which enables grating-based phase contrast with a conventional (spatially incoherent) X-ray source through the addition of a source grating (G0). The three-grating setup (G0, G1, G2) produces moiré fringes whose analysis — via **phase stepping** — yields the three contrast signals simultaneously from a single acquisition series.

Key characteristics:
- Micro-focus laboratory X-ray source
- Three-grating Talbot–Lau interferometry (G0, G1, G2)
- Phase stepping acquisition protocol
- Simultaneous retrieval of absorption, differential phase, and dark-field images
- Flexible geometry for adapting grating separation and energy

---

## What we do

- **Hardware development and characterisation.** Design, assembly, and systematic characterisation of the interferometer, including source and detector optimisation, grating alignment, and system stability studies.
- **Image acquisition and processing.** Implementation and optimisation of phase stepping protocols and phase retrieval algorithms; analysis of contrast-to-noise and spatial resolution trade-offs across the three channels.
- **Validation against Monte Carlo simulation.** Cross-validation of experimental images against our simulation pipelines (see [Monte Carlo simulation]({{ site.url }}{{ site.baseurl }}/research/simulation/)), using the SyRIS framework to verify the accuracy of the simulation chain.
- **Application to breast and chest imaging.** *Ex vivo* and preclinical studies in collaboration with our clinical partners (see [Preclinical imaging]({{ site.url }}{{ site.baseurl }}/research/preclinical/)).

---

## Selected publications

- *Verification of the SyRIS simulation framework for a Talbot–Lau interferometric phase contrast imaging system with a micro-focus X-ray source.* Sánchez-Lara, García Pinto, Chevalier (2022).

---

*See also our [publications page]({{ site.url }}{{ site.baseurl }}/publications/) for the full list.*
