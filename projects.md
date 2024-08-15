---
layout: default
title: Projects
permalink: /projects
---

{% for project in site.projects %}
<p>
  <a href="{{ project.url }}">{{ project.title }}</a>
  <br>
</p>
{% endfor %}