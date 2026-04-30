---
title: "Research — XTALIS"
layout: researchlay
excerpt: "XTALIS — grating-based phase contrast X-ray imaging system developed at UCM."
sitemap: false
permalink: /research/xtalis/
---

# XTALIS

**Grating-based phase contrast X-ray imaging system.**

<p markdown="0"><img src="{{ site.url }}{{ site.baseurl }}/images/xtalis/xtalis_logo_white.png" alt="XTALIS" style="display:block;height:52px;width:auto;margin:0 0 20px;" /></p>

XTALIS is our home-built X-ray phase contrast imaging system, based on **Talbot–Lau grating interferometry** with a micro-focus laboratory X-ray source. Developed entirely in-house, it is the central experimental platform of this research line, providing data for validation studies, algorithm development, and preclinical imaging.

---

## Why phase contrast?

Conventional radiography exploits the absorption of X-rays in tissue, which provides limited contrast between soft tissues of similar density. **Phase contrast imaging** complements absorption by exploiting the refractive index of materials, giving access to two additional contrast channels:

- **Differential phase contrast** — sensitive to the gradient of the refractive index; reveals interfaces and structural details invisible to absorption.
- **Dark-field contrast** — sensitive to small-angle scattering; particularly valuable in lung imaging (alveolar microstructure) and in characterising microcalcifications and fibrous tissue in the breast.

This is especially relevant in mammography and lung imaging, where subtle soft-tissue differences are diagnostically decisive.

---

## The XTALIS system

XTALIS implements the **Talbot–Lau interferometer** geometry, enabling grating-based phase contrast with a conventional (spatially incoherent) X-ray source through a source grating (G0). The three-grating setup (G0, G1, G2) produces moiré fringes whose analysis — via **phase stepping** — yields the three contrast signals simultaneously from a single acquisition series.

<p markdown="0"><img src="{{ site.url }}{{ site.baseurl }}/images/xtalis/Sistema.png" alt="The XTALIS grating interferometry system at UCM Imaging Lab" style="width:100%;border-radius:3px;margin:12px 0 6px;"><em style="display:block;text-align:right;font-size:12px;color:#888;margin-bottom:18px;">The XTALIS Talbot–Lau grating interferometry system at the UCM Imaging Lab.</em></p>

Key characteristics:
- Micro-focus laboratory X-ray source
- Three-grating Talbot–Lau interferometry (G0, G1, G2)
- Phase stepping acquisition protocol
- Simultaneous retrieval of absorption, differential phase, and dark-field images
- Flexible geometry for adapting grating separation and energy

---

## Image acquisition

A single phase stepping series yields three simultaneous contrast images. The example below shows a typical acquisition from XTALIS: absorption, differential phase contrast, and dark-field.

<p markdown="0"><img src="{{ site.url }}{{ site.baseurl }}/images/xtalis/Adquisicion_1.png" alt="Three contrast channels from XTALIS: absorption, differential phase contrast, dark-field" style="width:100%;border-radius:3px;margin:12px 0 6px;"><em style="display:block;text-align:right;font-size:12px;color:#888;margin-bottom:18px;">Example acquisition: absorption (left), differential phase contrast (centre), dark-field (right).</em></p>

---

## What we do

- **Hardware development and characterisation.** Design, assembly, and systematic characterisation of the interferometer: source and detector optimisation, grating alignment, and stability studies.
- **Image acquisition and processing.** Implementation and optimisation of phase stepping protocols and phase retrieval algorithms; analysis of CNR and spatial resolution trade-offs across the three channels.
- **Validation against Monte Carlo simulation.** Cross-validation of experimental images against our simulation pipelines (see [Monte Carlo simulation]({{ site.url }}{{ site.baseurl }}/research/simulation/)), using the SyRIS framework.
- **Application to breast and chest imaging.** *Ex vivo* and preclinical studies in collaboration with clinical partners (see [Preclinical imaging]({{ site.url }}{{ site.baseurl }}/research/preclinical/)).

---

## XPCIpy &mdash; software toolkit

We have developed **XPCIpy**, an open-source Python toolkit for X-ray phase-contrast imaging, covering phase stepping analysis, phase retrieval, dark-field extraction, and simulation utilities for grating-based systems. Published in *Optics Express* (2025).

<a href="{{ site.url }}{{ site.baseurl }}/research/xtalis/xpcipy/" class="btn btn-default btn-sm">XPCIpy &rarr;</a>

---

## Selected publications

- *Verification of the SyRIS simulation framework for a Talbot–Lau interferometric phase contrast imaging system with a micro-focus X-ray source.* Sánchez-Lara A, García Pinto D, Chevalier del Río M. *Physica Medica* (2022).
- *XPCIpy: A Python toolkit for X-ray phase-contrast imaging.* García Pinto D et al. *Optics Express* 33, 45949 (2025). [View &rarr;](https://opg.optica.org/oe/fulltext.cfm?uri=oe-33-22-45949)

---

*See also our [publications page]({{ site.url }}{{ site.baseurl }}/publications/) for the full list.*
