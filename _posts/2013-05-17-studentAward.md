---
layout: post
title:  "Douglas Chidester - 2013 Student of the Year"
date:   2013-05-17 09:00:00 -0700
categories: jekyll update
active: news
images:
  - image_path: /assets/img/student-of-the-year/douglasChidester.jpg
    title: Douglas Chidester
---

{: .center}
Douglas Chidester was named the 2012-2013 Computer Science Student of the Year. Congratulations Douglas!
<!--more-->
{% for image in page.images %}
  <div class="student-year">
    <a href="{{ image.image_path }}">
	<img src="{{ image.image_path }}" class="img-responsive" alt="{{ image.title }}">
    </a>
  </div>
{% endfor %}
