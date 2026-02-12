---
layout: guest
title: Amy Carney
description: Information about my podcast guest Amy Carney
permalink: /guest/amy-carney/
categories: guests
slug: "amy-carney"
---



<img src="{{ "/img/guest/amy-carney.jpg" | relative_url }}" alt="" class="guest-img">

<p>I’m a web designer and developer. I’m also an Alaskan and Kansan. Mum, wife and middle child.</p>

<h2>Podcast Episodes Featuring {{ page.name }}</h2>

<ul>
{% assign guest_episodes = site.posts | where_exp: "post", "post.guests contains page.slug" %}
{% for episode in guest_episodes %}
  <li>
    <a href="{{ episode.url | relative_url }}">{{ episode.title }}</a> ({{ episode.date | date: "%B %d, %Y" }})
  </li>
{% endfor %}
</ul>