---
layout: page
title: Categories
permalink: /categories/
---

<div class="categories">
  <div class="category-cards">
    {% for category in site.categories %}
      <div class="category-card">
        <h2><a href="/categories/{{ category[0] | slugify }}/">{{ category[0] | capitalize }}</a></h2>
        {% assign count = category[1] | size %}
        <p>{{ count }} post{% if count != 1 %}s{% endif %}</p>
      </div>
    {% endfor %}
  </div>
</div>