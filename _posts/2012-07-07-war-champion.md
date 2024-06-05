---
date: 2018-11-22 12:26:40
layout: post
title: War Champion
subtitle: 2D Games, Android
description: "World Invasion is a 2D skill-based game for Android. The goal of this game is to overcome various obstacles at each increasingly difficult level."
## image: https://res.cloudinary.com/dm7h7e8xj/image/upload/v1559822138/theme9_v273a9.jpg
image: /assets/img/WarChampion/1.png
optimized_image: /assets/img/WarChampion/Main.png
## optimized_image: https://res.cloudinary.com/dm7h7e8xj/image/upload/c_scale,w_380/v1559822138/theme9_v273a9.jpg
category: 2D Unity Game
tags:
  - 2D Games
  - Android
author: soultanfaiz
paginate: true
---

{{page.description}}


### Gameplay Footage

> Tap the left or right side of the photo below to view game screenshots.

<!-- HTML Structure -->
<div class="custom-container">
  <!-- Carousel items loop -->
  <div id="myCarousel" class="carousel slide" data-ride="carousel">
    <div class="carousel-inner">
      {% assign active = true %}
      {% for i in (1..14) %}
      <div class="carousel-item {% if active %}active{% endif %}">
        <img src="{{ site.baseurl }}/assets/img/WarChampion/{{ i }}.png" class="carousel-image" alt="Image {{ i }}">
      </div>
      {% assign active = false %}
      {% endfor %}
    </div>
    <a class="carousel-control-prev" href="#myCarousel" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#myCarousel" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</div>













