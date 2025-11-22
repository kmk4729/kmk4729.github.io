---
title: "Blog"
layout: page
permalink: /blog/
---

## 기술 블로그

개발 후기·이슈·알고리즘 문제풀이·실험 노트 등 자유롭게 기록합니다.

### 최근 포스트

{% for post in site.posts limit:10 %}
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: '%Y-%m-%d' }})
{% endfor %}

[더 많은 글 보기](/blog/)
