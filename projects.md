---
layout: default
title: Projects
---

# Projects

Here are some things I’ve built recently:

<ul>
  {% for project in site.data.projects %}
    <li>
      <h3><a href="{{ project.url }}">{{ project.name }}</a></h3>
      <p>{{ project.description }}</p>
    </li>
  {% endfor %}
</ul>

> Want to collaborate? [Contact me →](/contact)
