---
layout: post
title:  "CS Club 2014 - 2015 T-shirt"
date:   2014-03-04 09:00:00 -0700
categories: jekyll update
active: news
images:
  - image_path: /assets/img/news/csclub_tshirt_2014.png
    title: CS Club t-shirt
---

The CS Club winning t-shirt design with a circuit brain design by CS student Michelle Sandstrom. Help support SBCC's own Computer Science club. Help support SBCC's own Computer Science Club. You can place your order by emailing the [CS Club](mailto:sbcccsclub@gmail.com)
<!--more-->
{% for image in page.images %}
  <div class="center-image">
    <a href="{{ image.image_path }}">
	<img src="{{ image.image_path }}" class="img-responsive" alt="{{ image.title }}">
    </a>
  </div>
{% endfor %}
