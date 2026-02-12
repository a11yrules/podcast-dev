---
layout: guest
title: Kelsey Byers
description: Information about my podcast guest Kelsey Byers
permalink: /guest/kelsey-byers/
categories: guests
slug: "kelsey-byers"
---



<img src="/podcast-dev/img/guest/kelsey-byers.jpg" alt="" class="guest-img">

<p>Plant scientist. </p>

<h2>Podcast Episodes Featuring {{ page.name }}</h2>

<ul>
{% assign guest_episodes = site.posts | where_exp: "post", "post.guests contains page.slug" %}
{% for episode in guest_episodes %}
  <li>
    <a href="{{ episode.url | relative_url }}">{{ episode.title }}</a> ({{ episode.date | date: "%B %d, %Y" }})
  </li>
{% endfor %}
</ul>
