---
layout: post
title:  "Michelle Sandstrom - 2016 Student of the Year"
date:   2016-04-28 09:00:00 -0700
categories: jekyll update
active: news
images:
  - image_path: /assets/img/student-of-the-year/michelle.jpg
    title: Michelle Sandstorm
---

{: .center}
Michelle Sandstrom was named the 2015-2016 Computer Science Student of the Year. Congratulations Michelle!
<!--more-->
{% for image in page.images %}
  <div class="student-year">
    <a href="{{ image.image_path }}">
      <img src="{{ image.image_path }}" class="img-responsive" alt="{{ image.title }}">
    </a>
  </div>
{% endfor %}
