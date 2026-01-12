---
layout: default
title: Soundbites
permalink: /soundbites/
---

<h1>Soundbites</h1>


<ul>
{% assign soundbites_posts = site.posts | where: "categories", "soundbites" %}
{% for post in soundbites_posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>