---
title: "UCM Imaging Lab - Research"
layout: textlay
excerpt: "Research lines of the UCM Imaging Lab."
sitemap: false
permalink: /research/
---

# Research

Our research addresses the development and validation of emerging X-ray imaging technologies for medical applications. We work across five interconnected areas — from instrumentation to computational validation through *virtual clinical trials* — combining hardware, Monte Carlo simulation, deep learning, and preclinical experimentation, with a strong translational component in collaboration with hospitals and clinical partners.

---

{% assign number_printed = 0 %}
{% for line in site.data.researchlist %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix" style="margin-bottom: 22px;">
<div style="border-top: 5px solid {{ line.color }}; border: 1px solid #e2e6ea; border-radius: 0 0 4px 4px; padding: 18px 20px 16px; min-height: 190px;">
<h3 style="margin-top: 0; font-size: 17px;"><a href="{{ site.url }}{{ site.baseurl }}/research/{{ line.url }}/" style="color: {{ line.color }}; text-decoration: none;">{{ line.title }}</a></h3>
<p style="color: #888; font-style: italic; font-size: 12.5px; margin: 0 0 10px;">{{ line.subtitle }}</p>
<p style="font-size: 13.5px; color: #444; margin-bottom: 12px;">{{ line.description }}</p>
<a href="{{ site.url }}{{ site.baseurl }}/research/{{ line.url }}/" class="btn btn-default btn-sm">Read more &rarr;</a>
</div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}
