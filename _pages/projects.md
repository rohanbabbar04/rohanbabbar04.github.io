---
layout: page
title: Software / Open-source
permalink: /software/
description: Projects which I built, maintain and contribute to
nav: true
nav_order: 3
---

<div class="projects">
{% assign sorted_projects = site.projects | sort: "importance" %}
  <div class="project-list">
    {% for project in sorted_projects %}
        {% include project_showcase.liquid %}
    {% endfor %}
  </div>
</div>
