---
layout: post
title:  "Science Discovery Day at SBCC 2015"
date:   2015-03-17 09:00:00 -0700
categories: jekyll update
active: news
images:
  - image_path: /assets/img/science-day-2015/sdd6.jpg
  - image_path: /assets/img/science-day-2015/sdd3.jpg
    title: Stephen and his flashing goggles
  - image_path: /assets/img/science-day-2015/sdd1.jpg
    title: Banana piano
  - image_path: /assets/img/science-day-2015/sdd2.jpg
    title: Michelle demonstrating her game
  - image_path: /assets/img/science-day-2015/sdd6.jpg
    title: Volunteers and helpers for Science Discovery Day 2015
  - image_path: /assets/img/science-day-2015/sdd7.jpg
    title: The Crew... pre-jump
  - image_path: /assets/img/science-day-2015/sdd8.jpg
    title: Jumping ...
  - image_path: /assets/img/science-day-2015/sdd9.jpg
    title: Still jumping
  - image_path: /assets/img/science-day-2015/sdd5.jpg
    title: Jocelyn and Michelle
  - image_path: /assets/img/science-day-2015/sdd4.jpg
    title: Jocelyn
---

<!--more-->

{% for item in page.images %}
  <div class="col-lg-4 col-sm-6">
    <a href="{{ item.url }}" class="science-photos-2016-box">
      <img src="{{ item.image_path }}" class="img-responsive" alt="{{ item.title }}">
      <div class="portfolio-box-caption">
	<div class="portfolio-box-caption-content">
	  <div class="title-category text-faded">
	    {{ item.title }}
	  </div>
	</div>
      </div>
    </a>
  </div>
{% endfor %}
