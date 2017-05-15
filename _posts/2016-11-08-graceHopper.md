---
layout: post
title:  "SBCC Sends Students to Grace Hopper Celebration 2016"
date:   2016-11-08 09:00:00 -0700
categories: jekyll update
active: news
images:
  - image_path: /assets/img/grace-hopper-2016/gh1.jpg
    title: Students at Grace Hopper Conference 2016
  - image_path: /assets/img/grace-hopper-2016/gh5.jpg
    title: Student Group - Day 1
  - image_path: /assets/img/grace-hopper-2016/gh3.jpg
    title: Keynote Speeches
  - image_path: /assets/img/grace-hopper-2016/gh2.jpg
    title: Student Group - Day 2
  - image_path: /assets/img/grace-hopper-2016/gh8.jpg
    title: Jackie and Sofia
  - image_path: /assets/img/grace-hopper-2016/gh9.jpg
    title: Google Booth - Making emoticons from Code
  - image_path: /assets/img/grace-hopper-2016/gh11.jpg
    title: Jackie and Clio
  - image_path: /assets/img/grace-hopper-2016/gh13.jpg
    title: Theresa, Brie, Olivia, Jessica, Bronwen, and Dehlia
---

Santa Barbara City College sent 14 Students to Grace Hopper Celebration - Anita Borg Institute 2016 in Houston, Texas. The SBCC group at the conference (from left to right) includes Breanna Minnick, Clio Ramirez, Jessica Martinez, Simrik Manandhar, Celina Lazaro, Madeline London, Selah Argent, Sarah Rich, Karina Portugal, Jackie Kuehn, Bronwen Moore, Olivia Mora, Theresa Quisao, Michelle Sandstrom, Sofia Hamrin, and Aime Rodriguez. Missing from photo: Kimberly Todd.

<!--more-->
{% for item in page.images %}
  <div class="col-lg-4 col-sm-6">
    <a href="{{ item.image_path }}" class="grace-hopper-2016-box">
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
