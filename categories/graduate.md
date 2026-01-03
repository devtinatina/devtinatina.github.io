---
layout: page
title: 대학원
permalink: /categories/graduate/
---

<div class="category-posts">
{% for post in site.categories.graduate %}
  <article class="post-item">
    <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
    <p class="post-meta">{{ post.date | date: "%Y년 %m월 %d일" }}</p>
    <p>{{ post.excerpt }}</p>
  </article>
{% endfor %}
</div>
