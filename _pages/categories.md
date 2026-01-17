---
layout: page
title: Categories
permalink: /categories/
---

<div class="categories">
  <h1>Categories</h1>
  <div class="category-cards">
    {% for category in site.categories %}
      <div class="category-card">
        <h2><a href="/categories/{{ category[0] | slugify }}/">{{ category[0] | capitalize }}</a></h2>
        <p>{{ category[1] | size }} post{{ category[1] | size | pluralize }}</p>
      </div>
    {% endfor %}
  </div>
</div>