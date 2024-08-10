---
title: "Projects"
date: 2024-08-10
---

Hello! This is a cool test.

## Projects

<ul>
  {% for project in site.projects %}
    <li><a href="{{ project.url }}">{{ project.title }}</a></li>
  {% endfor %}
</ul>