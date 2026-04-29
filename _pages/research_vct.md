---
title: "Research — Virtual Clinical Trials"
layout: researchlay
excerpt: "End-to-end virtual clinical trials framework for in silico evaluation of imaging technologies."
sitemap: false
permalink: /research/vct/
---

# Virtual Clinical Trials

**In silico evaluation of imaging technologies.**

Validating a new imaging modality clinically is slow and resource-intensive. *Virtual clinical trials* (VCT) provide a complementary and increasingly recognised path: a computational framework that integrates **digital patient models**, **physically accurate simulation**, and **virtual observers**, enabling us to compare technologies, optimise acquisition parameters, and explore clinical scenarios in a fully controlled *in silico* environment — before any patient exposure.

---

## The VCT framework

A complete VCT pipeline consists of three coupled components:

1. **Digital phantoms** — computational models of patients or organs that provide realistic anatomy and tissue properties. We use and contribute to the **VICTRE** digital breast phantom (Virtual Imaging Clinical Trial for Regulatory Evaluation, FDA), which models compressed breast anatomy with glandular and adipose tissue distributions and can include simulated lesions (masses, microcalcifications).

2. **Image simulation** — a physically accurate Monte Carlo simulation engine that models the full X-ray imaging chain: source spectrum, beam shaping, phantom interaction (including scatter), detector response, and image formation (see [Monte Carlo simulation]({{ site.url }}{{ site.baseurl }}/research/simulation/)). The output is a synthetic but physically realistic image that would correspond to a real acquisition.

3. **Virtual observers** — mathematical models of image reading that evaluate the diagnostic information in each image. These range from classical model observers (channelised Hotelling observer, non-prewhitening matched filter) to deep-learning-based observers trained on synthetic data.

---

## What we do

- **Framework development.** We develop and maintain an end-to-end VCT pipeline that integrates the VICTRE phantom, our GAMOS/MIMAC simulation chain, and observer models for task-based image quality assessment.
- **Technology comparison.** Quantitative comparison of imaging modalities (e.g. digital mammography vs. tomosynthesis vs. phase contrast), evaluating detection performance for clinically relevant tasks.
- **Acquisition optimisation.** Systematic study of the effect of acquisition parameters (dose, geometry, energy) on observer performance, allowing evidence-based protocol design.
- **Evaluation of AI methods.** Use of VCT-generated cohorts to benchmark detection and classification algorithms in a controlled setting, complementing the studies in our [Deep Learning]({{ site.url }}{{ site.baseurl }}/research/deep-learning/) research line.
- **Regulatory and translational relevance.** The VCT approach is increasingly recognised by regulatory agencies (FDA, CE) as a valid evidence pathway for the evaluation of new imaging devices and AI software.

---

## Collaborations

Our VCT work builds on established international platforms and is developed in collaboration with clinical partners at the **Hospital Universitario 12 de Octubre** and within the **IMPACT** consortium.

---

*See also our [publications page]({{ site.url }}{{ site.baseurl }}/publications/) for the full list.*
