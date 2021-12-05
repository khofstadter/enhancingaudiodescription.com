---
layout: default
title: Events
permalink: /events/
image: 
video_embed: 
---

<div class="container">
<h1>Events</h1>
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
