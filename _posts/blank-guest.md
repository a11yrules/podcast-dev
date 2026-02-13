---
# step 1. save as "2026-01-01-guest-name.md" and update front matter
layout: guest
title: # insert {guest_name}
description: Information about my podcast guest # insert {guest_name}
permalink: /guest/.../ # replace ... with {first-last} name
categories: guests
slug: "" # insert {first-last} name
---

<!-- step 2. insert guest image -->
<img src="{{ "/img/guest/guest-name.jpg" | relative_url }}" alt="" class="guest-img">

<!-- step 3. insert guest bio -->
<p>insert guest bio</p>

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