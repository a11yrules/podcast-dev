---
layout: guest
title: Eric Bailey
description: Information about my podcast guest Eric Bailey
bio: "Eric is a designer who works for an agency in Massachussetts. He also writes about usability and accessibility for publications such as CSS-Tricks and Smashing Magazine."
image: "/img/guest/eric-bailey.png"
permalink: /guest/eric-bailey/
categories: guests
slug: "eric-bailey"
---

<img src="{{ page.image | relative_url }}" alt="" class="guest-img">

<p>{{ page.bio }}</p>

<h2>Podcast Episodes Featuring {{ page.name }}</h2>

<ul>
{% assign guest_episodes = site.posts | where_exp: "post", "post.guests contains page.slug" %}
{% for episode in guest_episodes %}
  <li>
    <a href="{{ episode.url | relative_url }}">{{ episode.title }}</a> ({{ episode.date | date: "%B %d, %Y" }})
  </li>
{% endfor %}
</ul>