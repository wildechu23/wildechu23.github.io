---
layout: page
title: Projects
permalink: /projects
---

A list of personal projects I've worked/am working on.

{% for project in site.projects reversed %}
<div class="project-entry">
  <a href="{{ project.url }}" class="project-link">{{ project.title }}</a>
  <small>{{ project.date | date: "%B %Y" }}</small>
  <br>
</div>
{% endfor %}
