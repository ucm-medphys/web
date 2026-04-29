---
title: "XPCIpy — Python toolkit for X-ray phase-contrast imaging"
layout: researchlay
excerpt: "XPCIpy: open-source Python package for grating-based X-ray phase-contrast imaging."
sitemap: false
permalink: /research/xtalis/xpcipy/
---

# XPCIpy

**Open-source Python toolkit for X-ray phase-contrast imaging.**

XPCIpy is a Python package developed at the UCM Imaging Lab to support research in grating-based X-ray phase-contrast imaging. It provides a modular set of tools covering the full workflow from raw phase stepping data to quantitative image reconstruction, with support for simulation-based validation.

The package was developed in the context of the [XTALIS]({{ site.url }}{{ site.baseurl }}/research/xtalis/) experimental system and is described in detail in our [*Optics Express* publication (2025)](https://opg.optica.org/oe/fulltext.cfm?uri=oe-33-22-45949).

---

## Features

- **Phase stepping analysis.** Extraction of absorption, differential phase, and dark-field signals from phase stepping data using curve-fitting and Fourier-based methods.
- **Phase retrieval.** Quantitative phase reconstruction from differential phase contrast images, including integration and iterative approaches.
- **Dark-field extraction.** Processing of the visibility-reduction signal for characterisation of scattering materials (e.g. lung microstructure, breast microcalcifications).
- **Simulation utilities.** Tools for generating and analysing synthetic phase stepping data, suitable for algorithm validation and virtual clinical trial workflows.
- **Flexible design.** Developed for the XTALIS system but applicable to general Talbot–Lau interferometry setups.

---

## Publication

<div class="well" style="margin-top:12px;" markdown="0">
<p style="margin:0;"><strong>XPCIpy: A Python toolkit for X-ray phase-contrast imaging</strong><br>García Pinto D et al.<br><em>Optics Express</em> 33, 45949 (2025) &nbsp;&middot;&nbsp; <a href="https://opg.optica.org/oe/fulltext.cfm?uri=oe-33-22-45949" target="_blank">View at Optics Express &rarr;</a></p>
</div>

---

*&larr; Back to [XTALIS]({{ site.url }}{{ site.baseurl }}/research/xtalis/)*
