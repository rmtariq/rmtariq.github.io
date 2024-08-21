---
layout: default
title: Home
---

Welcome to my blog! Here you'll find posts about various topics.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

