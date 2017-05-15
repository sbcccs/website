---
layout: post
title:  "CS Club 2015 - 2016 T-shirt"
date:   2015-11-15 09:00:00 -0700
categories: jekyll update
active: news
images:
  - image_path: /assets/img/news/csclub_tshirt_2015.png
    title: CS Club t-shirt
---

The CS Club winning t-shirt design with a chef flipping bits by James Howard and CS student Michelle Sandstrom. Help support SBCC's own Computer Science club. Place your orders by emailing the [CS Club](mailto:sbcccsclub@gmail.com)
<!--more-->
{% for image in page.images %}
  <div class="center-image">
    <a href="{{ image.image_path }}">
      <img src="{{ image.image_path }}" class="img-responsive" alt="{{ image.title }}">
    </a>
  </div>
{% endfor %}
