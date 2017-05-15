---
layout: post
title:  "Daniel Luft-Martinez - 2017 Student of the Year"
date:   2017-05-08 09:00:00 -0700
categories: jekyll update
active: news
images:
  - image_path: /assets/img/student-of-the-year/danielLuftMartinez.jpg
    title: Daniel Luft-Martinez
---

{: .center}
Daniel Luft-Martinez was named the 2016-2017 Computer Science Student of the Year. Congratulations Daniel!
<!--more-->
{% for image in page.images %}
  <div class="student-year">
    <a href="{{ image.image_path }}">
      <img src="{{ image.image_path }}" class="img-responsive" alt="{{ image.title }}">
    </a>
  </div>
{% endfor %}
