---
layout: page
title: Investment
permalink: /categories/investment/
---

<div class="category-posts">
  <h1>Investment Posts</h1>
  <ul class="post-list">
    {% assign sorted_posts = site.categories.investment | sort: 'date' | reverse %}
    {% for post in sorted_posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
        <h2>
          <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>
</div>