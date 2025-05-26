---
layout: default
title: 기술 블로그
---

# 📝 기술 블로그

아래는 제가 작성한 기술 관련 글들입니다.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>

