---
layout: default
title: Guests
permalink: /guests/
categories: guests
---

<h1>Guests</h1>

<ul>
{% for post in site.posts %}
  {% if post.categories == "guests" %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>