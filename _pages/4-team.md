---
layout: page
title: Team
permalink: /team/
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

## Research Team
<div class="container">
  <div class="row animate">
    {% if site.posts.size > 0 %}
      {% for post in site.posts %}
        {% if post.tags contains "research team"%}
        {% include article-no-date.html %}
         {% endif %}
      {% endfor %}
    {% endif %}
  </div>
</div>

## Administration Team
<div class="container">
  <div class="row animate">
    {% if site.posts.size > 0 %}
      {% for post in site.posts %}
        {% if post.tags contains "admin team"%}
        {% include article-no-date.html %}
         {% endif %}
      {% endfor %}
    {% endif %}
  </div>
</div>

## Advisory Panel
<div class="container">
  <div class="row animate">
    {% if site.posts.size > 0 %}
      {% for post in site.posts reversed %}
        {% if post.tags contains "advisory panel"%}
        {% include article-no-date.html %}
         {% endif %}
      {% endfor %}
    {% endif %}
  </div>
</div>

We would like to thank [Lewis Thresh](https://www.linkedin.com/in/lewis-thresh-59636510b/), [Morgan French](https://www.linkedin.com/in/morgan-french-19a437160/), [Elfed Howells](https://www.linkedin.com/in/elfedhowells/) and [John Whiston](https://rts.org.uk/person/john-whiston), whose work contributed to the success of the first part of our EAD research in 2015-2017.