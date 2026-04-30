---
title: "Research — MIMAC"
layout: researchlay
excerpt: "MIMAC: Mammographic Image Monte Carlo code — a GAMOS-based pipeline for digital mammography simulation."
sitemap: false
permalink: /research/simulation/mimac/
---

# MIMAC

**Mammographic Image Monte Carlo code.**

<div style="margin: 18px 0 24px;">
<img src="{{ site.url }}{{ site.baseurl }}/images/mimac/logo_mimac.png" alt="MIMAC logo" style="height: 56px; display: block; margin: 0;" />
</div>

**MIMAC** (*Mammographic Image Monte Carlo code*) is our open-source simulation pipeline for digital mammography, built on [GAMOS](http://fismed.ciemat.es/GAMOS/) and integrated with the [VICTRE digital breast phantom](https://github.com/DIDSR/VICTRE) developed by the FDA. MIMAC produces physically realistic synthetic mammographic images under fully controlled, reproducible conditions.

The code is publicly available on GitHub: **[PREDICO-Project/MIMAC](https://github.com/PREDICO-Project/MIMAC)**

---

### What MIMAC does

MIMAC models the full imaging chain for a digital mammography system:

- **X-ray source** — spectrum generation and beam geometry
- **Breast phantom** — integration with the VICTRE voxelised digital breast phantom (heterogeneous glandular tissue, skin, lesion models)
- **Particle transport** — Geant4/GAMOS physics for photon interactions, scatter, and fluorescence
- **Detector response** — energy deposition and signal formation in flat-panel detectors
- **Output** — projection images in standard format, ready for image quality and observer studies

---

### Applications

- **Image quality studies** — contrast, noise, spatial resolution under different acquisition conditions
- **Observer performance** — detection and discrimination tasks (lesions, calcifications)
- **AI training data** — large cohorts of annotated synthetic images for training and benchmarking deep learning models (see [Deep Learning]({{ site.url }}{{ site.baseurl }}/research/deep-learning/))
- **Dosimetry** — mean glandular dose estimation across tube voltages, target/filter combinations, and breast compositions
- **Technology comparison** — systematic in-silico evaluation as part of our [Virtual Clinical Trials]({{ site.url }}{{ site.baseurl }}/research/vct/) framework

---

### Publications

- *Simulation of digital mammographic images using GAMOS: Proof of concept.* Lozano FR, Sánchez-Lara V, Huerga C, Martínez-Gómez LC, García Pinto D. [Physica Medica 135 (2025)](https://www.physicamedica.com/article/S1120-1797(25)00105-X/fulltext){:target="_blank"}
- *PS07.40 Simulation of digital mammographic image using GAMOS.* García Pinto D et al. Physica Medica — EFOMP/ESTRO congress (2024)

---

*See also [Monte Carlo simulation]({{ site.url }}{{ site.baseurl }}/research/simulation/) and the [publications page]({{ site.url }}{{ site.baseurl }}/publications/).*
