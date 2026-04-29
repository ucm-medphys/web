---
title: "UCM Imaging Lab - Publications"
layout: gridlay
excerpt: "Publications of the UCM Imaging Lab."
sitemap: false
permalink: /publications/
---

# Publications

**Full scientific output also available at the [UCM Research Portal](https://produccioncientifica.ucm.es/grupos/5241/detalle).**

---

## Group highlights

{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  {% if publi.image and publi.image != "" %}
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  {% endif %}
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p>&nbsp;</p>

## Full list of publications

{% for publi in site.data.publist %}
{{ publi.title }}<br />
<em>{{ publi.authors }}</em><br />
<a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
<p> </p>
{% endfor %}
