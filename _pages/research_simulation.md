---
title: "Research — Monte Carlo simulation"
layout: researchlay
excerpt: "Monte Carlo simulation pipelines for medical imaging — Geant4, GAMOS, MIMAC, and phase contrast."
sitemap: false
permalink: /research/simulation/
---

# Monte Carlo simulation

**Geant4 / GAMOS pipelines for medical image simulation.**

Monte Carlo simulation is a central tool in our research. We use it to design and characterise imaging systems, study dosimetric aspects, generate physically accurate synthetic images, and feed our [virtual clinical trial]({{ site.url }}{{ site.baseurl }}/research/vct/) framework with realistic data — all in a fully controlled computational environment.

We work primarily with **Geant4** and **[GAMOS](http://fismed.ciemat.es/GAMOS/)** (Geant4-based Architecture for Medicine-Oriented Simulations), an extension of Geant4 developed at CIEMAT designed specifically for medical physics applications.

---

### Research lines

<div class="research-grid" markdown="0">
<div class="research-grid-item">
<div class="research-card">
<div class="research-card-body">
<h3><a href="{{ site.url }}{{ site.baseurl }}/research/simulation/mimac/">MIMAC</a></h3>
<p class="research-card-subtitle">Mammographic Image Monte Carlo code</p>
<p>Open-source pipeline for digital mammography simulation built on GAMOS and integrated with the VICTRE digital breast phantom. Produces realistic synthetic mammographic images for image quality studies, AI training, and dosimetry.</p>
<a href="{{ site.url }}{{ site.baseurl }}/research/simulation/mimac/" class="btn btn-default btn-sm">Read more &rarr;</a>
</div>
</div>
</div>
<div class="research-grid-item">
<div class="research-card">
<div class="research-card-body">
<h3><a href="{{ site.url }}{{ site.baseurl }}/research/simulation/pci/">Phase contrast simulation</a></h3>
<p class="research-card-subtitle">Talbot–Lau interferometry in GAMOS</p>
<p>Integration of grating-based phase contrast imaging into GAMOS, covering the full interferometric acquisition chain — phase stepping, contrast channel extraction, and verified against experimental data from XTALIS.</p>
<a href="{{ site.url }}{{ site.baseurl }}/research/simulation/pci/" class="btn btn-default btn-sm">Read more &rarr;</a>
</div>
</div>
</div>
</div>

---

*See also the [publications page]({{ site.url }}{{ site.baseurl }}/publications/) for the full list of outputs.*
