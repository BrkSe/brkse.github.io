---
layout: page
title: Burak - Java
permalink: /java/
---


### Kategorilere ait yazılar


{% for category in site.categories[java] %}
  <li>
    <ul>
    {% for posts in category %}
      {% for post in posts %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endfor %}
    {% endfor %}
    </ul>
  </li>
{% endfor %}

