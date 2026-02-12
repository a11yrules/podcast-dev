---
layout: guest
title: CB Averitt
description: Information about my podcast guest CB Averitt
permalink: /guest/cb-averitt/
categories: guests
slug: "cb-averitt"
---



<img src="{{ "/img/guest/cb-averitt.jpg" | relative_url }}" alt="" class="guest-img">

<p>I am with Deque Systems. It’s a pleasure to be here. I am a senior consultant with them. I do mostly work with dot-com clients. My client right now is a Fortune 50 company and I do a lot of volunteer work with trainings and things like that as well. It’s a pleasure to be here. </p>

<h2>Podcast Episodes Featuring {{ page.name }}</h2>

<ul>
{% assign guest_episodes = site.posts | where_exp: "post", "post.guests contains page.slug" %}
{% for episode in guest_episodes %}
  <li>
    <a href="{{ episode.url | relative_url }}">{{ episode.title }}</a> ({{ episode.date | date: "%B %d, %Y" }})
  </li>
{% endfor %}
</ul>