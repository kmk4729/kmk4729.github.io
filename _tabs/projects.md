---
layout: page
title: 프로젝트
permalink: /projects/
icon: fas fa-project-diagram
---

이곳은 저의 GitHub 프로젝트 목록입니다.

<div class="project-list">
  {% for project in site.data.projects %}
    <div class="project-item">
      <h3><a href="{{ project.url }}" target="_blank" rel="noopener noreferrer">{{ project.name }}</a></h3>
    </div>
  {% endfor %}
</div>
