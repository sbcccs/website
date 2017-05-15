---
layout: post
title:  "Andrea Brenner - 2014 Student of the Year"
date:   2014-05-08 09:00:00 -0700
categories: jekyll update
active: news
images:
  - image_path: /assets/img/student-of-the-year/andrea.jpg
    title: Andrea Brenner
---

{: .center}
Andrea Brenner was named the 2013-2014 Computer Science Student of the Year. Congratulations Andrea!
<!--more-->
{% for image in page.images %}
  <div class="student-year">
    <a href="{{ image.image_path }}">
      <img src="{{ image.image_path }}" class="img-responsive" alt="{{ image.title }}">
    </a>
  </div>
{% endfor %}
