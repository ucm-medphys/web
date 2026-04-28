---
title: "Research - Monte Carlo simulation"
layout: textlay
excerpt: "Monte Carlo simulation pipelines for medical imaging — Geant4, GAMOS, and the MIMAC code."
sitemap: false
permalink: /research/simulation/
---

# Monte Carlo simulation

**Geant4 / GAMOS pipelines for medical image simulation.**

Monte Carlo simulation is a central tool in our research line. We use it to design and characterize imaging systems, to study dosimetric aspects, and to feed our *virtual clinical trial* framework with synthetic but physically accurate images.

## Tools and frameworks

We work primarily with **Geant4** and **GAMOS** —a Geant4-based architecture for medicine-oriented simulations developed by the CIEMAT— complemented with selected developments in **GATE** when relevant.

## What we do

- **MIMAC** — *Mammographic Image MC code*. A simulation pipeline for digital mammography, built on GAMOS and integrated with the **VICTRE digital breast phantom**. MIMAC produces realistic synthetic mammographic images that can be used as input for image quality studies, observer studies, and AI training.
- **System modelling.** Detailed Monte Carlo models of the XTALIS phase-contrast setup and of clinical mammography systems, used to study acquisition geometry, dose, and detector response.
- **Cross-validation with experiment.** Comparison of simulated and experimental images, used both to validate the simulation chain and to calibrate the experimental setups.
- **Synthetic data for AI.** Generation of large, controlled cohorts of simulated images used to train and benchmark deep-learning methods (see [Deep Learning]({{ site.url }}{{ site.baseurl }}/research/deep-learning)).

## Selected publications

- *Simulation of digital mammographic images using GAMOS (Geant4-based architecture for medicine-oriented simulations)*. Lozano Martínez, Sánchez-Lara, Huerga Cabrerizo, García Pinto et al. (2024).
- [por completar — añadir más publicaciones representativas]

---

**Other research areas:** [XTALIS]({{ site.url }}{{ site.baseurl }}/research/xtalis) · [Virtual Clinical Trials]({{ site.url }}{{ site.baseurl }}/research/vct) · [Deep Learning]({{ site.url }}{{ site.baseurl }}/research/deep-learning) · [Preclinical imaging]({{ site.url }}{{ site.baseurl }}/research/preclinical)

[&larr; Back to Research]({{ site.url }}{{ site.baseurl }}/research)
