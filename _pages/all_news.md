---
title: "News"
layout: default
excerpt: "AI research group at AGU"
sitemap: false
permalink: /allnews.html
---
# News

<ul class="list-group list-group-flush">
{% for post in site.categories.news %}
<li class="list-group-item pl-0">{{post.date | date_to_string}} {{post.excerpt}}<a href="{{ post.url }}" class="stretched-link"></a></li>
{% endfor %}
</ul>
