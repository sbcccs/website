---
layout: post
title:  "Allison Van Pelt - 2010 Student of the Year"
date:   2010-05-14 09:00:00 -0700
categories: jekyll update
active: news
images:
  - image_path: /assets/img/student-of-the-year/allison.jpg
    title: Allison Van Pelt
---

{: .center}
Allison Van Pelt was named the 2009-2010 Computer Science Student of the Year. Congratulations Allison!
<!--more-->
{% for image in page.images %}
  <div class="student-year">
    <a href="{{ image.image_path }}">
	<img src="{{ image.image_path }}" class="img-responsive" alt="{{ image.title }}">
    </a>
  </div>
{% endfor %}
