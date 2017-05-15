---
layout: page
title: Certificate of Achievement - Computer Science
permalink: /certificate/
active: degrees
header: [DEPARTMENT REQUIREMENTS (COMPLETE 32.5 - 35.5 UNITS), CLASS UNITS (23.5 - 25.5 UNITS)]
subheader: ["Plus at least two courses from the following:", "Class Units (7 - 12 units)"]
dict: 
   - title: "CS 101 - Computer Concepts"
     units: 4 units
   - title: "CS 105 - Theory and Practice I or"
     units: 3 units
   - title: "CS 120 - Java Programming"
     units: 3 units
   - title: "CS 130 - Introduction to the Linux Operating System"
     units: 2.5 units
   - title: "CS 137 - C Programming or"
     units: 3 units
   - title: "CS 140 - Object-Oriented Programming Using C++"
     units: 4 units
   - title: "MATH 107 - Intermediate Algebra or"
     units: 4 units
   - title: "MATH 111 - Intermediate Algebra Major"
     units: 5 units
   - title: "PHIL 205 - Introduction to Logic"
     units: 3 units
   - title: "PHYS 102 - Introduction to Physics for Science Majors"
     units: 4 units
subdict:
   - title: "CS 106 - Theory and Practice II"
     units: 3 units
   - title: "CS 107 - Computer and Architecture and Organization"
     units: 3 units
   - title: "CS 111 - HTML and Webmastering"
     units: 3 units
   - title: "CS 137 - C Programming or"
     units: 3 units
   - title: "CS 140 - Object-Oriented Programming Using C++"
     units: 4 units
---

<div class="certificate">
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
	    <thead><tr>
		{% assign cols = page.subheader %}
		{% for col in cols %}
		<th>{{ col }}</th>
		{% endfor %}
	    </tr></thead>
	    <tbody>
		{% for item in page.subdict %}
		<tr><td>{{ item.title }}</td><td>{{ item.units }}</td></tr>
		{% endfor %}
	    </tbody>
	</table>
    </div>

    <p>*NOTE: A course used to satisfy one requirement may not be used to satisfy another requirement (double-counting is not allowed).</p>
    <p>Students must complete all department requirements for the certificate with a cumulative GPA of 2.0 or better. Candidates for a Certificate of Achievement are required to complete at least 20% of the department requirements through SBCC.</p>
    <p>For further information, contact the <a href="http://www.sbcc.edu/counselingcenter">Counseling Center</a>, 954-0581 ext. 2285, or <a href="#">Dr. Dean Nevins</a>, Department Chair, (805) 730-5191</p>
    <p><a href="http://www.sbcc.edu/catalog/2015_2016/departments/14_Computer%20Science.pdf">College Requirements</a></p>

</div>
