---
layout: post
title:  "Aaron Eidelson - 2009 Student of the Year"
date:   2009-05-15 09:00:00 -0700
categories: jekyll update
active: news
images:
  - image_path: /assets/img/student-of-the-year/aaron.jpg
    title: Aaron Eidelson
---

{: .center}
Aaron Eidelson was named the 2008-2009 Computer Science Student of the Year. Congratulations Aaron!
<!--more-->
{% for image in page.images %}
  <div class="student-year">
    <a href="{{ image.image_path }}">
	<img src="{{ image.image_path }}" class="img-responsive" alt="{{ image.title }}">
    </a>
  </div>
{% endfor %}
