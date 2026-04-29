---
title: "Research — Monte Carlo simulation"
layout: researchlay
excerpt: "Monte Carlo simulation pipelines for medical imaging — Geant4, GAMOS, and the MIMAC code."
sitemap: false
permalink: /research/simulation/
---

# Monte Carlo simulation

**Geant4 / GAMOS pipelines for medical image simulation.**

Monte Carlo simulation is a central tool in our research. We use it to design and characterise imaging systems, study dosimetric aspects, generate physically accurate synthetic images, and feed our [virtual clinical trial]({{ site.url }}{{ site.baseurl }}/research/vct/) framework with realistic data — all in a fully controlled computational environment.

---

## Tools and frameworks

We work primarily with **Geant4** and **[GAMOS](http://fismed.ciemat.es/GAMOS/)** (Geant4-based Architecture for Medicine-Oriented Simulations), an extension of Geant4 developed at CIEMAT and designed specifically for medical physics applications. We complement these with **GATE** for selected use cases.

These tools provide:
- Full particle transport physics (photon interactions, scatter, fluorescence)
- Detailed modelling of detectors, sources, and beam geometry
- Flexible scorer and scoring plugins for dose and image formation

---

## MIMAC — Mammographic Image MC code

**MIMAC** (*Mammographic Image Monte Carlo code*) is our in-house simulation pipeline for digital mammography, built on GAMOS and integrated with the **VICTRE digital breast phantom** (Virtual Imaging Clinical Trial for Regulatory Evaluation, FDA). MIMAC produces realistic synthetic mammographic images that can be used for:

- Image quality studies (contrast, noise, spatial resolution)
- Observer performance studies (detection, discrimination tasks)
- Training and benchmarking of deep-learning methods (see [Deep Learning]({{ site.url }}{{ site.baseurl }}/research/deep-learning/))
- Dosimetric analysis under different acquisition conditions

---

## What we do

- **System modelling.** Detailed Monte Carlo models of the XTALIS phase-contrast setup (see [XTALIS]({{ site.url }}{{ site.baseurl }}/research/xtalis/)) and of clinical mammography and tomosynthesis systems, used to study acquisition geometry, scatter fractions, dose, and detector response.
- **Cross-validation with experiment.** Systematic comparison of simulated and experimental images, used both to validate the simulation chain and to calibrate the experimental setups.
- **Synthetic data for AI.** Generation of large, annotated cohorts of simulated images as controlled training and benchmarking datasets for deep-learning methods.
- **Dosimetry.** Estimation of mean glandular dose and organ doses under different acquisition protocols and patient models.

---

## Selected publications

- *Simulation of digital mammographic images using GAMOS (Geant4-based architecture for medicine-oriented simulations).* Lozano Martínez, Sánchez-Lara, Huerga Cabrerizo, García Pinto et al. (2024).
- *Verification of the SyRIS simulation framework for a Talbot–Lau interferometric phase contrast imaging system with a micro-focus X-ray source.* Sánchez-Lara, García Pinto, Chevalier (2022).

---

*See also our [publications page]({{ site.url }}{{ site.baseurl }}/publications/) for the full list.*
