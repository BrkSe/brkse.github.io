---
layout: page
title: Burak - Java
permalink: /java/
---


### Java diline ait yazılar


{% for category in site.categories.['java'] %}
  <li><a name="{{ category | first }}">{{ category | first }}</a>
    <ul>
    {% for posts in category %}
      {% for post in posts %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endfor %}
    {% endfor %}
    </ul>
  </li>


