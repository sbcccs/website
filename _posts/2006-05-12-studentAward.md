---
layout: post
title:  "Eric Drafahl - 2006 Student of the Year"
date:   2006-05-12 09:00:00 -0700
categories: jekyll update
active: news
images:
  - image_path: /assets/img/student-of-the-year/ericDrafahl.jpg
    title: Eric Drafahl
---

{: .center}
Eric Drafahl was named the 2005-2006 Computer Science Student of the Year. Congratulations Eric!
<!--more-->
{% for image in page.images %}
  <div class="student-year">
    <a href="{{ image.image_path }}">
	<img src="{{ image.image_path }}" class="img-responsive" alt="{{ image.title }}">
    </a>
  </div>
{% endfor %}
