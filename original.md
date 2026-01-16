---
layout: default
title: The Original
permalink: /series/the-original/
---

<h1>The Original</h1>

<ul>
{% assign original_posts = site.posts | where: "categories", "original" %}
{% for post in original_posts %}
  <!-- <li><a href="{{ post.url }}">{{ post.title }}</a></li> -->
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>