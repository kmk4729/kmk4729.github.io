---
title: "Projects"
layout: page
permalink: /projects/
---

# 대표 프로젝트

{% for project in site.projects %}
## {{ project.title }}

**설명**: {{ project.excerpt }}

**주요 기술:** {{ project.tags | join: ', ' }}

[자세히 보기]({{ project.url }})
{% endfor %}

(위 반복문은 실제 `_projects/` 폴더 내 md 파일 자동 리스트업)
