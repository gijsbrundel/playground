---
layout: default
title: Welkom
---

# Hallo, ik ben [jouw naam]

Welkom op mijn portfolio. Hier kun je mijn werk en blogs bekijken.

## Projecten
- 📁 [Project A](#)
- 📁 [Project B](#)

## Laatste blogposts
<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> – {{ post.date | date: "%d %B %Y" }}</li>
  {% endfor %}
</ul>
