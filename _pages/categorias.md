---
layout: page
title: Categorias
permalink: /categorias/
---
{% for category in site.categories %}
  <h2>{{ category[0]}}</h2>
  <ul>
    {% for post in category[1] %}
        {% for post in site.tags %}
          <h3>{{ tag[0]}}</h3>
            <li><a href="{{ post.url }}">{{ post.title }}</a></li>
        {% endfor %}
    {% endfor %}
  </ul>
{% endfor %}
