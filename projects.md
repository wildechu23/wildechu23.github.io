---
layout: page
title: Projects
permalink: /projects
---

{% for project in site.projects %}
<p>
  <a href="{{ project.url }}" class="project-link">{{ project.title }}</a>
  <br>
</p>
{% endfor %}