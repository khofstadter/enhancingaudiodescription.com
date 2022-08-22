---
layout: post-team
title:  Emily Wood
description: Student Intern
date:   2015-01-04
image:  '/images/team-intern-emily-feature.jpg'
image-alt: 'Photo of a Emily.'
image-header: '/images/team-intern-emily.jpg'
tags:   [team, intern]
---
<!-- begin hero -->
  <div class="container">
    <div class="row">
      <div class="col col-12">
        <div class="hero2__inner">
          <div class="hero2__left">
            <h1 class="post__title">{{ page.title | escape }}</h1>
          {%if page.description %}
            {{ page.description }}
          {% endif %}
          <br><br>
          <p>My name is Emily Wood. I am a 22 year old student from Birmingham. This year, I am entering my final year of an MSci Psychology degree at the University of York, specialising in neuroscience and neuroimaging. My work experiences include volunteering as an English teacher in Cambodia, working as an Inclusive Community Coordinator for LGBTQIA+ students at my university, and completing a research project investigating social robots for which I was awarded ‘Best Research in Social Sciences’ by the YorRobotics Committee.
          <br><br>
          I am now working with the Royal National Institute for the Blind, researching audio description for documentary television programs. I intend to work with blind and partially sighted individuals to learn about their experiences with audio described documentary programs, establishing the strengths and weaknesses of the audio description currently available and proposing potential improvements.
          </p>
           </div>
          <div class="hero2__right">
              <img class="lazy" data-src="{{page.image-header}}" alt="{{page.image-alt}}">
        </div>
      </div>
    </div>
  </div>
