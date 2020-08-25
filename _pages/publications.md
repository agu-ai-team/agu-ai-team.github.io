---
title: "AGU AI - Publications"
layout: publications_layout
excerpt: "AGU AI -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

## Group highlights

## Full List

{% for publi in site.data.publication_list %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
