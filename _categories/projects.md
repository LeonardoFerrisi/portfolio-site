---
title: "Projects"
date: 2024-08-10
---

The following are the projects that have their own page through my site.
The documentation for my many projects is actively a work in progress.

<ul>
  {% for project in site.projects %}
    <li><a href="{{ project.url }}" style="color: blue;">{{ project.title }}</a></li>
  {% endfor %}
</ul>