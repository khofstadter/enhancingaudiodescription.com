---
layout: page
title: Events
permalink: /events/
image: 
video_embed: 
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
        {% if post.tags[0] == "event" %}
        {% include article.html %}
         {% endif %}
      {% endfor %}
    {% endif %}
  </div>
</div>
