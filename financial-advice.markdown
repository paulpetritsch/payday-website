---
layout: default
title: Finanztipps
permalink: /financial-advice/
---
# Finanztipps

<ul>
  {% for post in site.categories.financial-advice %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>