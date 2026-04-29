---
title: "Research — Deep Learning"
layout: researchlay
excerpt: "Deep learning for synthetic data generation, image processing, and reconstruction in medical imaging."
sitemap: false
permalink: /research/deep-learning/
---

# Deep Learning

**Neural networks applied to medical X-ray imaging.**

Deep learning is a transversal tool in our research line: both a research object —where we develop methods specific to the challenges of medical X-ray imaging— and a technical instrument integrated across all our other research areas.

---

## Context and motivation

Medical imaging AI faces a fundamental data bottleneck: annotated clinical datasets are scarce, heterogeneous, and subject to strict ethical and legal constraints. We address this by combining our [Monte Carlo simulation]({{ site.url }}{{ site.baseurl }}/research/simulation/) pipelines with generative and discriminative deep-learning methods to produce, process, and evaluate synthetic medical images in a fully controlled setting.

---

## What we do

### Synthetic data generation
We use our Monte Carlo simulation engine as a controllable data generator, and complement it with **generative models** (including GANs and diffusion-based approaches) to:
- Produce large, annotated synthetic datasets for training and benchmarking image-analysis algorithms
- Augment real datasets by bridging the gap between simulation and acquisition
- Model the variability of patient anatomy and pathology in a statistically controlled way

### Image processing and reconstruction
We develop and evaluate deep-learning methods for specific tasks arising in phase contrast and mammographic imaging:
- **Noise reduction** — learned denoising for low-dose acquisitions
- **Phase retrieval** — neural network-based alternatives to analytical phase stepping inversion
- **Super-resolution** — spatial resolution enhancement in simulated and experimental images
- **Artefact correction** — compensation of grating imperfections and beam-hardening effects in phase contrast images

### Integration with Virtual Clinical Trials
Deep-learning models are used as components of our [VCT pipeline]({{ site.url }}{{ site.baseurl }}/research/vct/) in two roles:
- As **virtual observers**: trained classifiers or detection networks evaluated on synthetic image cohorts
- As **image-processing modules under evaluation**: comparing AI-enhanced images against reference acquisition protocols

### AI-aware imaging system design
We study the joint optimisation of imaging acquisition parameters and the AI methods that consume the resulting images — recognising that the optimal imaging chain for a human reader may differ from the optimal chain when an algorithm is the end consumer.

---

*See also our [publications page]({{ site.url }}{{ site.baseurl }}/publications/) for the full list.*
