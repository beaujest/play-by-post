---
layout: default
title: Matches
---

<h1>Matches</h1>
<ul>
  {% for match in site.matches %}
    <li>
      <a href="{{ match.url }}">{{ match.title }} - level {{ match.level }}</a>
    </li>
  {% endfor %}
</ul>
