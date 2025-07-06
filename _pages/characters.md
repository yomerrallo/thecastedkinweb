---
title: "Characters"
permalink: /characters/
layout: single
---

# Characters

Meet the known characters from the world of The Casted Kin. Click on a character to learn more!

<ul>
  {% for character in site.characters %}
    <li><a href="{{ character.url }}">{{ character.title }}</a> - {{ character.role | default: 'Role/Title' }}</li>
  {% endfor %}
</ul>

*Character bios and images will appear here.* 