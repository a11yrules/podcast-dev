---
layout: guest
title: Patrick Burke
description: Information about my podcast guest Patrick Burke
permalink: /guest/patrick-burke/
categories: guests
slug: "patrick-burke"
---

<img src="{{ "/img/guest/pat-burke.jpg" | relative_url }}" alt="" class="guest-img">

<p>Patrick Burke is a screen reader user.</p>

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