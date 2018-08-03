---
layout: page
title: Cursos
permalink: /cursos/
---

Estos son los últimos cursos que he realizado:

<ul>
{% for curso in site.data.cursos %}
  <li>
    <a href="{{ curso.url }}" target="_blank">
      {{ curso.nombre }}
    </a>
  </li>
{% endfor %}
</ul>