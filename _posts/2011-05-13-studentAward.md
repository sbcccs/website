---
layout: post
title:  "Chad Simmons - 2011 Student of the Year"
date:   2011-05-13 09:00:00 -0700
categories: jekyll update
active: news
images:
  - image_path: /assets/img/student-of-the-year/chad.jpg
    title: Chad Simmons
---

{: .center}
Chad Simmons was named the 2010-2011 Computer Science Student of the Year. Congratulations Chad!
<!--more-->
{% for image in page.images %}
  <div class="student-year">
    <a href="{{ image.image_path }}">
	<img src="{{ image.image_path }}" class="img-responsive" alt="{{ image.title }}">
    </a>
  </div>
{% endfor %}
