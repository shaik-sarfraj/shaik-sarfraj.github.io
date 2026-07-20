---
layout: single
title: "Projects"
permalink: /portfolio/
author_profile: false
---

A collection of GIS, urban analytics, Python-based spatial analysis, urban design, and planning research projects.

---

## Featured Projects

{% assign projects = site.portfolio %}

{% for project in projects %}

<div class="project-card">

<h3>
<a href="{{ project.url }}">
{{ project.title }}
</a>
</h3>

<p>
{{ project.excerpt }}
</p>

<a class="project-button" href="{{ project.url }}">
View Project →
</a>

</div>

{% endfor %}
