---
layout: post
title:  "Russell Fenenga - 2015 Student of the Year"
date:   2015-05-08 09:00:00 -0700
categories: jekyll update
active: news
images:
  - image_path: /assets/img/student-of-the-year/russell.jpg
    title: Russell Fenenga
---

{: .center}
Russell Fenenga was named the 2014-2015 Computer Science Student of the Year. Congratulations Russell!
<!--more-->
{% for image in page.images %}
  <div class="student-year">
    <a href="{{ image.image_path }}">
      <img src="{{ image.image_path }}" class="img-responsive" alt="{{ image.title }}">
    </a>
  </div>
{% endfor %}

