---
layout: post
title:  "Renamed and Renumbered CS Courses"
date:   2015-06-04 09:00:00 -0700
categories: jekyll update
active: news
images:
  - image_path: /assets/img/news/renumbered_courses2015.png
    title: Renumbered Courses
  - image_path: /assets/img/news/cs_courseflowchart_2015.png
    title: Course Flowchart
---

As you might have noticed, the CS Department has renamed and renumbered several core courses. It's part of an effort to improve the organization of our courses and better align with University transer models and course identification systems.<!--more--> Undoubtedly, this will create some short term confusion amongst students, faculty, and counselors. So, to keep things straight until we get the new names and numbers memorized, here is a table to help clarify the situation:

{% for image in page.images %}
  <div class="center-image">
    <a href="{{ image.image_path }}">
      <img src="{{ image.image_path }}" class="img-responsive" alt="{{ image.title }}">
    </a>
  </div>
{% endfor %}
