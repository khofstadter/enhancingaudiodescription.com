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

<div class="container">
  <h2>Visible Mending</h2>
  <p>Our newest and most successful production at the moment can be played with the embedded video player below. You can access the full film through the embedded video player below. There are two soundtracks available and you can select which one to listen to by going to the settings symbol (the cog) and selecting the soundtrack you'd like to listen to. By default, the video is set to the original soundtrack, so please change it to the EAD version before playing which is called 'English UK Audio Descriptions'.</p>
    <article class="post">
    <div class="post__content">
    <div style="padding:52.73% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/827066711?h=b05611ccb9" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>
    <br></div>
    </article>
    <h2>Videos</h2>
    This section contains a list of blog posts featuring our videos.
  <br><br>   
    <div class="row animate">
      {% if site.posts.size > 0 %}
        {% for post in site.posts %}
          {% if post.tags contains "video" %}
          {% if post.grid != false %}
          {% include article.html %}
          {% endif %}
          {% endif %}
        {% endfor %}
      {% endif %}
    </div>
  <h2>Podcasts</h2>
    <div class="row animate">
      {% if site.posts.size > 0 %}
        {% for post in site.posts %}
          {% if post.tags contains "podcast" %}
          {% if post.grid != false %}
          {% include article.html %}
          {% endif %}
          {% endif %}
        {% endfor %}
      {% endif %}
      <p>Our podcast can also be enjoyed via our playlist on our <a href="https://soundcloud.com/user-351945045">Soundcloud account</a>.</p>
    </div>
</div>