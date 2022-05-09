---
layout: page
title: Media
permalink: /media/
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


## Videos
<div class="container">
<article class="post">
<div class="post__content">
<p><iframe title="EAD introduction video." src="https://www.youtube.com/embed/JkbhY-Q8reI" loading="lazy" frameborder="0" allowfullscreen></iframe></p>
</div>
</article>

This section contains a list of blog posts featuring our videos.
<br><br>
  <div class="row animate">
    {% if site.posts.size > 0 %}
      {% for post in site.posts %}
        {% if post.tags contains "video" %}
        {% include article.html %}
         {% endif %}
      {% endfor %}
    {% endif %}
  </div>
</div>

<br>
<br>

## Podcasts
<div class="container">
This section contains a list of blog posts featuring our podcasts.
<br>
<br>
  <div class="row animate">
    {% if site.posts.size > 0 %}
      {% for post in site.posts %}
        {% if post.tags contains "podcast" %}
        {% include article.html %}
         {% endif %}
      {% endfor %}
    {% endif %}
     <p>Our podcast can also be enjoyed via our playlist on our <a href="https://soundcloud.com/user-351945045">Soundcloud account</a>.</p>
  </div>
</div>
<br>
<br>