---
layout: post
title:  "Victor Moreira - 2007 Student of the Year"
date:   2007-05-18 09:00:00 -0700
categories: jekyll update
active: news
images:
  - image_path: /assets/img/student-of-the-year/withvictor.jpg
    title: Victor Moreira
---

{: .center}
Victor Moreira was named the 2006-2007 Computer Science Student of the Year. Congratulations Victor!
<!--more-->
{% for image in page.images %}
  <div class="student-year">
    <a href="{{ image.image_path }}">
	<img src="{{ image.image_path }}" class="img-responsive" alt="{{ image.title }}">
    </a>
  </div>
{% endfor %}
