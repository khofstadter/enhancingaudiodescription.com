---
layout: page
title: Outputs
permalink: /outputs/
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

## Journal Publications
<p>López, M., Kearney, G. and Hofstädter, K. (2021) <a href="https://jatjournal.org/index.php/jat/article/view/154">‘Enhancing Audio Description: Inclusive Cinematic Experiences Through Sound Design’ in Journal of Audiovisual Translation</a>. DOI: 10.1177/0264619620935935</p>
<p>López, M., Kearney, G. and Hofstädter, K. (2020) <a href="https://journals.sagepub.com/doi/full/10.1177/0264619620935935">‘Seeing films through sound: Sound design, spatial audio, and accessibility for visually impaired audiences’ in British Journal of Visual Impairment</a>. DOI: 10.1177/0264619620935935</p>
<p>López, M., Kearney, G. and Hofstädter, K. & Balla, G. (2020) <a href="https://www.tandfonline.com/doi/full/10.1080/25741136.2020.1832830">‘Enhancing audio description: accessible filmmaking, sound design and the importance of educating filmmakers.’ in Media Practice and Education</a> 21:4, 289-304. DOI: 10.1080/25741136.2020.1832830</p>
<p>López, M., Kearney, G. and Hofstädter, K. (2018) <a href="https://journals.sagepub.com/doi/10.1177/0264619618794750">‘Audio Description in the UK: What works, what doesn’t, and understanding the need for personalising access.’ in British Journal of Visual Impairment</a>, 36(3), pp. 274–291. DOI: 10.1177/0264619618794750</p>
<p>López, M. and Pauletto, S. (2009) <a href="https://www.semanticscholar.org/paper/The-Design-of-an-Audio-Film%3A-Portraying-Story%2C-and-Lopez-Pauletto/f0ab4f055dcee2f9a59dc07184e9175f4e0a7551">‘The Design of an Audio Film: Portraying Story, Action and Interaction through Sound’ in JMM: The Journal of Music and Meaning</a>, 8, Winter 2009.</p>
<br>
<br>

## Conference Papers and Presentation

<p>López, M., Kearney, G. and Hofstadter, K., ‘Enhancing Audio Description, Spatialisation and Accessibility in Film and Television’ in Reproduced Sound Conference, Southampton, UK, 15-17 November 2016. Read this paper in original format <a href="../assets/docs/papers/RS2016-paper-Lopez-et-al.pdf"> here</a> and its accessible version <a href="../assets/docs/papers/RS2016-paper-Lopez-et-al_accessible.pdf"> here</a>.
<br><br>
López, M., Kearney, G. and Hofstadter, K., ‘Sound Design and Accessibility in Film and Television’ in 140th International Audio Engineering Society Convention, Paris, France, 4-7 June 2016, (Tutorial).
<br><br>
López, M., ‘Perceptual evaluation of an audio film for visually impaired audiences’ in the Audio Engineering Society (AES) 138th Convention, Warsaw, Poland, 7-10 May 2015.
<br><br>
López, M. and Pauletto, S., ‘The Sound Machine: a study in storytelling through sound design’ in Proceedings of the 5th Audio Mostly Conference, Piteå, Sweden, 15-17 September 2010.
<br><br>
López, M. and Pauletto, S., ‘The Design of an Audio Film for the visually impaired’ in the 15th International Conference on Auditory Display (ICAD), Copenhagen, Denmark, 18-22 May 2009.
</p>
<br>
<br>

## Press
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

## Videos
<div class="container">
<article class="post">
<div class="post__content">
<p><iframe src="https://www.youtube.com/embed/JkbhY-Q8reI" loading="lazy" frameborder="0" allowfullscreen></iframe></p>
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

