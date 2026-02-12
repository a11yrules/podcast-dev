---
layout: guest
title: Sina Bahram
description: Information about my podcast guest Sina Bahram
permalink: /guest/sina-bahram/
categories: guests
slug: "sina-bahram"
---



<img src="{{ "/img/guest/sina-bahram.jpg" | relative_url }}" alt="" class="guest-img">

<p>Sina runs an accessibility firm called Prime Access Consulting. We do a lot of work with organizations especially in the cultural heritage sectors, like museums, and non-profits oriented around that space but also with start-ups and universities and larger companies on digital accessibility, whether that’s web accessibility, iPhone apps, digital interactives that involve large touch interfaces in museums, and applying the principles of inclusive and universal design to that so those types of experiences and technologies are available to the widest possible audience.</p>

<h2>Podcast Episodes Featuring {{ page.name }}</h2>

<ul>
{% assign guest_episodes = site.posts | where_exp: "post", "post.guests contains page.slug" %}
{% for episode in guest_episodes %}
  <li>
    <a href="{{ episode.url | relative_url }}">{{ episode.title }}</a> ({{ episode.date | date: "%B %d, %Y" }})
  </li>
{% endfor %}
</ul>