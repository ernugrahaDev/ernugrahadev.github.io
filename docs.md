---
layout: default
title: Documentation
permalink: /docs/
---

# Documentation
Tested on Debian 12 (amd-64)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%d %B %Y" }})</small>
    </li>
  {% endfor %}
</ul>
