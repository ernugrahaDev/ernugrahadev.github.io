---
layout: default
title: Documentation
permalink: /docs/
---

Tested on Debian 12 (amd-64)


{% assign grouped = site.posts | group_by: "category" %}

{% for category in grouped %}
## {{ category.name | capitalize }}

<ul>
  {% for post in category.items %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%d %B %Y" }})</small>
    </li>
  {% endfor %}
</ul>
{% endfor %}
