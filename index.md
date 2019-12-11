---
title:
nav: Start
layout: default
meta: Some info about Mentalt kombinat
changefreq: monthly
---

# Mentalt kombinat

Mentalt kombinat är en podcast som görs av Robin Fondberg ([@RobinFondberg](https://twitter.com/RobinFondberg)) och Martin Asperholm ([@MAsperholm](https://twitter.com/MAsperholm), [Asperholm.net](http://www.asperholm.net)), båda vid Avdelningen för psykologi på Karolinska institutet.

Här är en lista med de poddar som vi har gjort hittills:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%Y-%m-%d" }}: {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
