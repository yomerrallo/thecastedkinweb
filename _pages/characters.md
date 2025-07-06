---
title: "Characters"
permalink: /characters/
---

# Characters

*Meet the known characters from the game. Click on a character to learn more!*

<ul>
  {% for character in site.characters %}
    <li><a href="{{ character.url }}">{{ character.title }}</a> - {{ character.role | default: 'Role/Title' }}</li>
  {% endfor %}
</ul>

*Character bios and images will appear here.* 