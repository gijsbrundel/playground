---
layout: default
title: Welkom
---

# Hallo,

Welkom alhier. Een eerste opzet.

## Projecten
- 📁 [Project A](#)
- 📁 [Project B](#)

## Laatste posts
<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> – {{ post.date | date: "%d %B %Y" }}</li>
  {% endfor %}
</ul>
