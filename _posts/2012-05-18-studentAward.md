---
layout: post
title:  "Daniel Guimaraes - 2012 Student of the Year"
date:   2012-05-18 09:00:00 -0700
categories: jekyll update
active: news
images:
  - image_path: /assets/img/student-of-the-year/bigDanial.jpg
    title: Daniel Guimares
---

{: .center}
Daniel Guimares was named the 2011-2012 Computer Science Student of the Year. Congratulations Daniel!
<!--more-->
{% for image in page.images %}
  <div class="student-year">
    <a href="{{ image.image_path }}">
	<img src="{{ image.image_path }}" class="img-responsive" alt="{{ image.title }}">
    </a>
  </div>
{% endfor %}
