---
layout: default
title: Guests
permalink: /guests/
---

<h1>Guests - Nic version</h1>

<ul>
{% assign soundbites_posts = site.posts | where: "categories", "guests" %}
{% for post in soundbites_posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>