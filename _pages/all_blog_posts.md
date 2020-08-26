---
title: "AGU AI - Blog Posts"
layout: default
excerpt: "Blog Posts"
sitemap: false
permalink: /blog/
---

# All Blog Posts

<ul class="list-group list-group-flush">
{% for post in site.categories.blog %}
<li class="list-group-item pl-0"><a href="{{ post.url }}">{{ post.title }} - {{ post.date | date_to_string}} </a> by {% assign author = site.people  | where: "name", post.author | first %}
<a href="{{ author.url}}"> {{ post.author }}</a></li>
{% endfor %}
</ul>
