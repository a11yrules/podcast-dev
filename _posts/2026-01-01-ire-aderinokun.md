---
layout: guest
title: Ire Aderinokun
description: Information about my podcast guest Ire Aderinokum
permalink: /guest/ire-aderinokun/
categories: guests
slug: "ire-aderinokum"
---

<img src="{{ "/img/ire-aderinokun.jpg" | relative_url }}" alt="" class="guest-img">

<p>Ire is a User Interface Designer & Front-End Developer based in Lagos, Nigeria</p>

<h2>Podcast Episodes Featuring {{ page.name }}</h2>

<ul>
{% assign guest_episodes = site.posts | where_exp: "post", "post.guests contains page.slug" %}
{% for episode in guest_episodes %}
  <li>
    <a href="{{ episode.url }}">{{ episode.title }}</a> ({{ episode.date | date: "%B %d, %Y" }})
  </li>
{% endfor %}
</ul>
