---
title: "UCM Imaging Lab - Research"
layout: textlay
excerpt: "Research lines of the UCM Imaging Lab."
sitemap: false
permalink: /research/
---

# Research

Our research addresses the development and validation of emerging X-ray imaging technologies for medical applications. We work across five interconnected areas — from instrumentation to computational validation through *virtual clinical trials* — combining hardware, Monte Carlo simulation, deep learning, and preclinical experimentation, with a strong translational component in collaboration with hospitals and clinical partners.

<div class="research-grid" markdown="0">

{% for line in site.data.researchlist %}
<div class="research-grid-item">
  <div class="research-card" style="border-top: 5px solid {{ line.color }};">
    <div class="research-card-body">
      <h3><a href="{{ site.url }}{{ site.baseurl }}/research/{{ line.url }}/" style="color: {{ line.color }};">{{ line.title }}</a></h3>
      <p class="research-card-subtitle">{{ line.subtitle }}</p>
      <p>{{ line.description }}</p>
      <a href="{{ site.url }}{{ site.baseurl }}/research/{{ line.url }}/" class="btn btn-default btn-sm">Read more &rarr;</a>
    </div>
  </div>
</div>
{% endfor %}

</div>
