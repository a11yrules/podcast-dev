---
layout: guest
title: Robert Jolly
description: Information about my podcast guest Robert Jolly
permalink: /guest/robert-jolly/
categories: guests
slug: "robert-jolly"
---



<img src="{{ "/img/robert-jolly.jpg" | relative_url }}" alt="" class="guest-img">

<p>Robert Jolly is an accessibility-focused product manager working for the U.S. government on GSA’s 10x Delivery Team. Robert was previously at Knowbility and was a member of the W3C’s Web Accessibility Initiative Education and Outreach Working Group.</p>

<h2>Podcast Episodes Featuring {{ page.name }}</h2>

<ul>
{% assign guest_episodes = site.posts | where_exp: "post", "post.guests contains page.slug" %}
{% for episode in guest_episodes %}
  <li>
    <a href="{{ episode.url | relative_url }}">{{ episode.title }}</a> ({{ episode.date | date: "%B %d, %Y" }})
  </li>
{% endfor %}
</ul>