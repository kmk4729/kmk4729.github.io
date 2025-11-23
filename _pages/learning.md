---
title: "Learning Notes"
layout: page
permalink: /learning/
---

## 기술 학습 노트

{% assign learning_posts = site.learning | sort: "date" | reverse %}
{% for post in learning_posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) ({{ post.date | date: "%Y-%m-%d" }})
{% endfor %}
