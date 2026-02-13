---
layout: guest
title: Dave Brown
description: Information about my podcast guest Dave Brown
permalink: /guest/dave-brown/
categories: guests
slug: "dave-brown"
---

<img src="{{ "/img/guest/dave-brown.jpg" | relative_url }}" alt="" class="guest-img">

<p>Dave Brown is a disabled radio show host.</p>

<!-- leave untouched -->
<h2>Podcast Episodes Featuring {{ page.name }}</h2>

<ul>
{% assign guest_episodes = site.posts | where_exp: "post", "post.guests contains page.slug" %}
{% for episode in guest_episodes %}
  <li>
    <a href="{{ episode.url | relative_url }}">{{ episode.title }}</a> ({{ episode.date | date: "%B %d, %Y" }})
  </li>
{% endfor %}
</ul>