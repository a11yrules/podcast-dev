---
layout: default
title: The Original
permalink: /the-original/
---

<h1>The Original</h1>

<ul>
{% for post in site.posts %}
  {% if post.category == "original" %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>