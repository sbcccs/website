---
layout: post
title:  "Science Discovery Day at SBCC 2016"
date:   2016-03-07 09:00:00 -0700
categories: jekyll update
active: news
images:
  - image_path: /assets/img/science-day-2016/sdd1.jpg
    title: Volunteers for Science Discovery Day 2016
  - image_path: /assets/img/science-day-2016/sdd2.jpg
    title: The popular Eggbot
  - image_path: /assets/img/science-day-2016/sdd5.jpg
    title: Nathalie and volunteers
  - image_path: /assets/img/science-day-2016/sdd3.jpg
    title: Jackie and Stephen
  - image_path: /assets/img/science-day-2016/sdd7.jpg
    title: Andrew and Colin
  - image_path: /assets/img/science-day-2016/sdd4.jpg
    title: The SBCC workers
  - image_path: /assets/img/science-day-2016/sdd6.jpg
    title: Stephen and the giant floor piano
  - image_path: /assets/img/science-day-2016/sdd8.jpg
    title: Wilhelm Scream!
---

<!--more-->

{% for item in page.images %}
  <div class="col-lg-4 col-sm-6">
    <a href="{{ item.image_path }}" class="science-photos-2016-box">
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
