---
layout: page
title: Software / Open-source
permalink: /software/
description: Things that I built, maintain and contribute to
nav: true
nav_order: 2
---

I'm passionate about high-performance, scientific computing and data analytics, with a focus on solving large-scale 
computational problems. I enjoy building, maintaining, and contributing to open-source research software.
Here are some of the projects I've spent far too many hours working on (and happily still do). 
You can find the rest of my contributions on my <a href="https://github.com/rohanbabbar04">GitHub</a>.

<div class="projects">
{% assign sorted_projects = site.projects | sort: "importance" %}
  <div class="project-list">
    {% for project in sorted_projects %}
        {% include project_showcase.liquid %}
    {% endfor %}
  </div>
</div>
