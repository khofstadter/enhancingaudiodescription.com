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
        {% if post.tags[0] == "press" %}
        {% if post.grid != false %}
        {% include article.html %}
         {% endif %}
         {% endif %}
      {% endfor %}
    {% endif %}
  </div>
</div>
