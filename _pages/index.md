---
layout: page
title: Home
id: home
permalink: /
---

# Welcome! 🌱

<strong>AMbassador list</strong>

<ul>
  {% assign recent_notes = site.notes
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
