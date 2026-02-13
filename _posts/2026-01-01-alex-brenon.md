---
layout: guest
title: Alex Brenon
description: Information about my podcast guest Alex Brenon
permalink: /guest/alex-brenon/
categories: guests
slug: "alex-brenon"
---

<img src="{{ "/img/guest/alex-brenon.jpg" | relative_url }}" alt="" class="guest-img">

<p>Alex is a recent graduate of Smith College, a developer who works in blended learning and teaching.</p>

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