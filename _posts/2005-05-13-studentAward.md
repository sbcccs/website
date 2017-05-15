---
layout: post
title:  "Ewelina Oboza - 2005 Student of the Year"
date:   2005-05-13 09:00:00 -0700
categories: jekyll update
active: news
images:
  - image_path: /assets/img/student-of-the-year/ewelina.jpg
    title: Ewelina Oboza
---

{: .center}
Ewelina Oboza was named the 2004-2005 Computer Science Student of the Year. Congratulations Ewelina!
<!--more-->
{% for image in page.images %}
  <div class="student-year">
    <a href="{{ image.image_path }}">
	<img src="{{ image.image_path }}" class="img-responsive" alt="{{ image.title }}">
    </a>
  </div>
{% endfor %}
