---
layout: guest
title: Denis Boudreau
description: Information about my podcast guest Denis Boudreau
permalink: /guest/denis-boudreau/
categories: guests
slug: "denis-boudreau"
---

<img src="{{ "/img/guest/denis-boudreau.jpg" | relative_url }}" alt="" class="guest-img">

<p>I'm from Montreal, Canada. I work for Deque Systems. I've been working in Accessibility for about 17 years, doing mostly consulting, and training, and strategy with different clients, and that's about it.</p>

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