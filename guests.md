---
layout: default
title: Guests
permalink: /guests/
---

<h1>Guests - Nic version</h1>

<ul>
{% assign soundbites_posts = site.posts | where: "categories", "guests" %}
{% for post in soundbites_posts %}
  <li><a href="/podcast/{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

<h2>Guests - copilot version</h1>

<!-- Alphabetical Navigation -->
<nav class="alphabet-nav">
  <ul>
    {% assign letters = "A,B,C,D,E,F,G,H,I,J,K,L,M,N,O,P,Q,R,S,T,U,V,W,X,Y,Z" | split: "," %}
    {% for letter in letters %}
      <li><a href="#{{ letter }}">{{ letter }}</a></li>
    {% endfor %}
  </ul>
</nav>

<!-- Guests Listing -->
<section class="guest-listing">
  {% assign guests = site.data.guests | sort: "last_name" %}
  {% for letter in letters %}
    {% assign guests_by_letter = guests | where_exp: "guest", "guest.last_name starts_with letter" %}
    {% if guests_by_letter != empty %}
      <h2 id="{{ letter }}">{{ letter }}</h2>
      <ul>
        {% for guest in guests_by_letter %}
          <li>
            <a href="{{ guest.url }}">
              {{ guest.first_name }} {{ guest.last_name }}
            </a>
          </li>
        {% endfor %}
      </ul>
    {% endif %}
  {% endfor %}
</section>