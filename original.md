---
layout: default
title: The Original
permalink: /the-original/
---

<h1>The Original</h1>

<ul>
{% assign soundbites_posts = site.posts | where: "categories", "original" %}
{% for post in soundbites_posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>