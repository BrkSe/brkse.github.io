---
layout: page
title: Burak - Java
permalink: /java/
---


### Java diline ait yazılar



  <li>
    <ul>
    {% for posts in category %}
      {% for post in posts %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endfor %}
    {% endfor %}
    </ul>
  </li>


