---
layout: page
title: Literatura
permalink: /categorias/
---

{% for category in site.categories %}
  <h3>{{ category[0] }}</h3>
  <ul>
    {% for post in category[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}

{% for post in site.categories.Literatura %}

{{ post.date | date_to_string }} [{{ post.title }}]({{ post.url }})
{% endfor %}
