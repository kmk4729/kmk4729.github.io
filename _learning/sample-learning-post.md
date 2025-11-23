---
title: "Jekyll 기본 개념"
layout: learning_post
date: 2025-11-23 10:00:00 +0900
---

Jekyll은 정적 사이트 생성기입니다. Markdown으로 작성된 콘텐츠를 HTML로 변환하여 웹사이트를 만듭니다.

### 주요 특징

*   **정적 사이트:** 데이터베이스 없이 HTML, CSS, JavaScript 파일로만 구성됩니다.
*   **마크다운 지원:** 글 작성이 쉽습니다.
*   **템플릿 엔진:** Liquid를 사용하여 동적인 콘텐츠를 생성합니다.

### Jekyll 설치

```bash
gem install jekyll bundler
```

### 새 프로젝트 생성

```bash
jekyll new my-awesome-site
cd my-awesome-site
bundle exec jekyll serve
```
