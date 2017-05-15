---
layout: page
title: Skills Competency Award - Web Programming
permalink: /webskills/
active: degrees
header: [DEPARTMENT REQUIREMENTS (COMPLETE 16 - 16.5 UNITS), CLASS UNITS]
dict:
   - title: "CIS 230 - Active Server Pages & VB Script or"
     units: 4 units
   - title: "CS 125 - C# Programming and"
     units: 3 units
   - title: "CS 127 - ASP.net using C#"
     units: 1.5 units
   - title: "CS 111 - HTML and Webmastering"
     units: 3 units
   - title: "CS 115 - JavaScript and Dynamic HTML"
     units: 3 units
   - title: "CS 116 - Web Server Programming"
     units: 3 units
   - title: "CS 105 - Theory and Practice I or"
     units: 3 units
   - title: "CS 120 - Java Programming"
     units: 3 units
---

<div class="web">
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
		<tr><td>{{ item.title }}</td><td>{{ item.units }}</td></tr>
		{% endfor %}
	    </tbody>
	</table>
    </div>

    <p>*NOTE: Students must complete the above courses with a grade of "C" or higher or credit in all courses.</p>
    <p>For further information, contact the <a href="http://www.sbcc.edu/counselingcenter">Counseling Center</a>, 954-0581 ext. 2285, or <a href="#">Dr. Dean Nevins</a>, Department Chair, (805) 730-5191</p>
    <p><a href="http://www.sbcc.edu/catalog/2015_2016/departments/14_Computer%20Science.pdf">College Requirements</a></p>

</div>
