---
layout: default
title: Soundbites
permalink: /soundbites/
---

<h1>Soundbites</h1>

<ul>
{% for post in site.posts %}
  {% if post.categories == "soundbites" %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>

<h2>Debugging Output</h2>
<pre>
{% for post in site.posts %}
- Title: {{ post.title }}
- Categories: {{ post.categories }}
- Permalink: {{ post.url }}
{% endfor %}
</pre>