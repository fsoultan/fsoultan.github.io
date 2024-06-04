---
date: 2018-11-22 12:26:40
layout: post
title: Mending Rakit PC
subtitle: 2D Games, PC
description: "'Mending Rakit PC' is a 2D game created using Unity and playable on PC. In this game, players embark on a mission to purchase PC components and assemble them according to a specified budget and specifications to complete levels."
## image: https://res.cloudinary.com/dm7h7e8xj/image/upload/v1559822138/theme9_v273a9.jpg
image: /assets/img/MendingRakitPC/1.png
optimized_image: /assets/img/MendingRakitPC/1.png
## optimized_image: https://res.cloudinary.com/dm7h7e8xj/image/upload/c_scale,w_380/v1559822138/theme9_v273a9.jpg
category: 2D Unity Game
tags:
  - 2D Games
  - PC
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
      {% for i in (1..8) %}
      <div class="carousel-item {% if active %}active{% endif %}">
        <img src="{{ site.baseurl }}/assets/img/MendingRakitPC/{{ i }}.png" class="d-block img-fluid" alt="Image {{ i }}">
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













