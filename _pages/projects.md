---
layout: page
title: Software / Open-source
permalink: /software/
description: Things that I built, maintain and contribute to
nav: true
nav_order: 2
---

<div class="projects">
{% assign sorted_projects = site.projects | sort: "importance" %}
  <div class="project-list">
    {% for project in sorted_projects %}
        {% include project_showcase.liquid %}
    {% endfor %}
  </div>
</div>
