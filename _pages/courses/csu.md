---
layout: page
title: CSU Transfer Courses
permalink: /csutransfer/
active: courses
header: [COURSES, SEMESTER OFFERED, TRANSFER CREDIT]
dict: 
   - title: "CS 101: Computer Concepts"
     link: "http://www.curricunet.com/sbcc/reports/course_outline_html.cfm?courses_id=6379"
     term: Fall / Spring
     transfer: UC / CSU
   - title: "CS 104: Introduction to Programming"
     link: "http://www.curricunet.com/sbcc/reports/course_outline_html.cfm?courses_id=7099"
     term: Fall / Spring
     transfer: UC / CSU
   - title: "CS 105: Theory and Practice I"
     link: "http://www.curricunet.com/sbcc/reports/course_outline_html.cfm?courses_id=3597"
     term: Fall / Spring
     transfer: UC / CSU
   - title: "CS 106: Theory and Practice II"
     link: "http://www.curricunet.com/sbcc/reports/course_outline_html.cfm?courses_id=3589"
     term: Fall / Spring
     transfer: UC / CSU
   - title: "CS 107: Computer Architecture & Organization"
     link: "http://www.curricunet.com/sbcc/reports/course_outline_html.cfm?courses_id=6509"
     term: Fall / Spring
     transfer: UC / CSU
   - title: "CS 108: Discrete Structures"
     link: "http://www.curricunet.com/sbcc/reports/course_outline_html.cfm?courses_id=7095"
     term: Fall / Spring
     transfer: UC / CSU
   - title: "CS 111: HTML and Webmastering"
     link: "http://www.curricunet.com/sbcc/reports/course_outline_html.cfm?courses_id=6401"
     term: Fall / Spring
     transfer: CSU
   - title: "CS 114: Python Programming"
     link: "http://www.curricunet.com/sbcc/reports/course_outline_html.cfm?courses_id=4533"
     term: TBD
     transfer: UC / CSU
   - title: "CS 115: Javascript And Dynamic HTML"
     link: "http://www.curricunet.com/sbcc/reports/course_outline_html.cfm?courses_id=6402"
     term: TBD
     transfer: CSU
   - title: "CS 116: Web Server Programming"
     link: "http://www.curricunet.com/sbcc/reports/course_outline_html.cfm?courses_id=6508"
     term: TBD
     transfer: CSU
   - title: "CS 123: Android Programming"
     link: "http://www.curricunet.com/sbcc/reports/course_outline_html.cfm?courses_id=3588"
     term: TBD
     transfer: UC / CSU
   - title: "CS 125: C# Programming"
     link: "http://www.curricunet.com/sbcc/reports/course_outline_html.cfm?courses_id=2723"
     term: TBD
     transfer: CSU
   - title: "CS 129: Java Server Programming"
     link: "http://www.curricunet.com/sbcc/reports/course_outline_html.cfm?courses_id=3595"
     term: TBD
     transfer: UC / CSU
   - title: "CS 130: Introduction to the Linux Operating System"
     link: "http://www.curricunet.com/sbcc/reports/course_outline_html.cfm?courses_id=3591"
     term: Fall / Spring
     transfer: UC / CSU
   - title: "CS 132: Digital Logic Design"
     link: "http://www.curricunet.com/sbcc/reports/course_outline_html.cfm?courses_id=7096"
     term: Fall
     transfer: UC / CSU
   - title: "CS 133: Introduction to Programming for Engineers"
     link: "http://www.curricunet.com/sbcc/reports/course_outline_html.cfm?courses_id=6377"
     term: Fall / Spring
     transfer: UC / CSU
   - title: "CS 137: C Programming"
     link: "http://www.curricunet.com/sbcc/reports/course_outline_html.cfm?courses_id=3586"
     term: Fall / Spring
     transfer: UC / CSU
   - title: "CS 140: Object-Oriented Programming Using C++"
     link: "http://www.curricunet.com/sbcc/reports/course_outline_html.cfm?courses_id=6375"
     term: Fall / Spring
     transfer: UC / CSU
   - title: "CS 165: Software Design Patterns"
     link: "http://www.curricunet.com/sbcc/reports/course_outline_html.cfm?courses_id=3592"
     term: Spring
     transfer: CSU
   - title: "CS 180: Software Engineering with UML"
     link: "http://www.curricunet.com/sbcc/reports/course_outline_html.cfm?courses_id=3593"
     term: Fall
     transfer: UC / CSU
   - title: "CS 187: iOS Programming"
     link: "http://www.curricunet.com/sbcc/reports/course_outline_html.cfm?courses_id=6511"
     term: Fall / Spring
     transfer: CSU
   - title: "CS 189: Programming Practicum"
     link: "http://www.curricunet.com/sbcc/reports/course_outline_html.cfm?courses_id=4536"
     term: TBD
     transfer: CSU
---

<div class="table-responsive">
  {% assign cols = page.header %}
  <table class="table table-bordered table-hover">
    <thead><tr>
    {% for col in cols %}
      <th>{{ col }}</th>
    {% endfor %}
    </tr></thead>
    <tbody>
    {% for item in page.dict %}
      <tr><td><a href="{{ item.link }}">{{ item.title }}</a></td><td>{{ item.term }}</td><td>{{ item.transfer }}</td></tr>
    {% endfor %}
    </tbody>
  </table>
</div>
