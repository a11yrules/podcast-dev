---
layout: guest
title: Alli Berry
description: Information about my podcast guest Alli Berry
permalink: /guest/alli-berry/
categories: guests
slug: "alli-berry"
---

<img src="{{ "/img/guest/alli-berry.jpg" | relative_url }}" alt="" class="guest-img">

<p>Alli is the SEO and content lead for the Ascent by the Motley Fool. Her part of the business, they are a sub-brand of that, and they're focused on creating free personal finance content, and her job is really to make sure our site is accessible … as accessible as possible for search engines, and to help our pages rank well, and to get our content to as many people as possible. And what's fortunate about SEO is that often what is accessible for search engines is also what is accessible for humans so by approaching websites from an SEO perspective they're at least on our way to helping make websites more accessible for humans too.</p>

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