---
layout: default
title: Soundbites
permalink: /soundbites/
---

<h1>Soundbites</h1>

<ul>
{% for post in site.posts %}
  {% if post.category == "soundbites" %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>