---
layout: page
title: Press
permalink: /press/
image: 
---

<head>
<style>
.page__info {
  max-width: 1024px;
  }
.page {
  max-width: 1024px;
}
</style>
</head>

<div class="container">
  <div class="row animate">
    {% if site.posts.size > 0 %}
      {% for post in site.posts %}
        {% if post.tags contains "press"%}
        {% include article-no-title.html %}
         {% endif %}
      {% endfor %}
    {% endif %}
  </div>
</div>
<br>
<br>
