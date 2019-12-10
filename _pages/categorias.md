---
layout: page
title: Categorias
permalink: /categorias/
---

{% for post in site.categories.Literatura %}
<li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
