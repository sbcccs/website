---
layout: page
title: Associate of Science - Computer Science
permalink: /associate/
active: degrees
header: [DEPARTMENT REQUIREMENTS (COMPLETE 33 UNITS), CLASS UNITS (27 UNITS)]
subheader: ["Plus at least 6 units from the following:", Class Units (6 units)]
dict:
   - title: "CS 105 - Theory and Practice I"
     units: 3 units
   - title: "CS 106 - Theory and Practice II"
     units: 3 units
   - title: "CS 107 - Computer Architecture and Organization"
     units: 3 units
   - title: "CS 108 - Discrete Structures"
     units: 4 units
   - title: "CS 140 - Object-Oriented Programming Using C++"
     units: 4 units
   - title: "MATH 150 - Calculus with Analytic Geometry I"
     units: 5 units
   - title: "PHYS 121 - Mechanics of Solids and Fluids"
     units: 5 units
subdict:
   - title: "CS 104 - Introduction to Programming"
     units: 3 units
   - title: "CS 111 - HTML and Webmastering"
     units: 3 units
   - title: "CS 115 - Javascript and Dynamic HTML"
     units: 3 units
   - title: "CS 116 - Webserver Programming"
     units: 3 units
   - title: "CS 120 - Java Programming"
     units: 3 units
   - title: "CS 123 - Android Programming"
     units: 1.5 units
   - title: "CS 130 - Introduction to the Linux Operating System"
     units: 2.5 units
   - title: "CS 132 - Digital Logic Design"
     units: 3 units
   - title: "CS 133 - Introduction to Programming for Engineers"
     units: 3 units
   - title: "CS 137 - C Programming"
     units: 3 units
   - title: "CS 165 - Software Design Patterns"
     units: 1.5 units
   - title: "CS 180 - Software Engineering with UML"
     units: 3 units
   - title: "CS 187 - iOS Programming"
     units: 3 units
   - title: "CS 189 - Programming Practicum"
     units: 1 unit
   - title: "MATH 160 - Calculus with Analytical Geometry II"
     units: 5 units
   - title: "MATH 200 - Multivariable Calculus"
     units: 4 units
   - title: "MATH 210 - Linear Algebra"
     units: 4 units
   - title: "MATH 220 - Differential Equations"
     units: 4 units
   - title: "PHIL 205 - Introduction to Logic"
     units: 3 units
   - title: "PHYS 122 - Electricity and Magnetism"
     units: 5 units
---

<div class="associate">
    <h3 style="text-align: center">Revised Requirements as of 2015 - 2016</h3>
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
    <p>*NOTE: PHYS 102 does not count toward department requirement if either PHYS 121 or 122 has been taken. MATH 250/260 may also count toward the elective requirement. A course used to satisfy one requirement may not be used to satisfy another requirement (double-counting is not allowed).</p>
    <p>For further information, contact the <a href="http://www.sbcc.edu/counselingcenter">Counseling Center</a>, 954-0581 ext. 2285, or <a href="#">Dr. Dean Nevins</a>, Department Chair, (805) 730-5191</p>
    <p><a href="http://www.sbcc.edu/catalog/2015_2016/departments/14_Computer%20Science.pdf">College Requirements</a></p>
</div>
