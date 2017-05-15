---
layout: page
title: Computer Science Students of the Year
permalink: /people/students-of-the-year/
active: people
dict:
   - student: Daniel Luft-Martinez
     year: 2016 - 2017
     post: "/jekyll/update/2017/05/08/studentAward.html"
   - student: Michelle Sandstrom
     year: 2015 - 2016
     post: "/jekyll/update/2016/04/28/studentAward.html"
   - student: Russell Fenenga
     year: 2014 - 2015
     post: "/jekyll/update/2015/05/08/studentAward.html"
   - student: Andrea Brenner
     year: 2013 - 2014
     post: "/jekyll/update/2014/05/08/studentAward.html"
   - student: Douglas Chidester
     year: 2012 - 2013
     post: "/jekyll/update/2013/05/17/studentAward.html" 
   - student: Daniel Guimaraes
     year: 2011 - 2012
     post: "/jekyll/update/2012/05/18/studentAward.html"
   - student: Chad Simmons
     year: 2010 - 2011
     post: "/jekyll/update/2011/05/13/studentAward.html"
   - student: Allison Van Pelt
     year: 2009 - 2010
     post: "/jekyll/update/2010/05/14/studentAward.html"
   - student: Aaron Eidelson
     year: 2008 - 2009
     post: "/jekyll/update/2009/05/15/studentAward.html"
   - student: Daniel Vucci
     year: 2007 - 2008
     post: "/jekyll/update/2008/05/16/studentAward.html"
   - student: Victor Moreira
     year: 2006 - 2007
     post: "/jekyll/update/2007/05/18/studentAward.html"
   - student: Eric Drafahl
     year: 2005 - 2006
     post: "/jekyll/update/2006/05/12/studentAward.html"
   - student: Ewelina Oboza
     year: 2004 - 2005
     post: "/jekyll/update/2005/05/13/studentAward.html"
   - student: Brian Weiner
     year: 2003 - 2004
   - student: Dominic Metzger
     year: 2002 - 2003
   - student: Matthew Baker
     year: 2001 - 2002
   - student: David Gowans
     year: 2000 - 2001
   - student: Dave Stewart
     year: 1999 - 2000
   - student: Randolph Evered
     year: 1998 - 1999
   - student: April Pingley
     year: 1997 - 1998
   - student: Brandon Lovelace
     year: 1996 - 1997
   - student: Don Adams
     year: 1995 - 1996
   - student: Steve Frost
     year: 1994 - 1995
   - student: Chicka Kono
     year: 1991 - 1992
   - student: Deborah Cass
     year: 1990 - 1991
   - student: Mary Ann Simmons
     year: 1989 - 1990
   - student: Richard Kenny
     year: 1988 - 1989
   - student: Michael Cervantes
     year: 1987 - 1988
   - student: David Robbins
     year: 1986 - 1987
   - student: Andrew Sobel
     year: 1984 - 1985
   - student: Daniel Esqueda
     year: 1983 - 1984
   - student: Wade Davis
     year: 1982 - 1983
   - student: David Ross
     year: 1980 - 1981
---

<div class="award-icon">
  <img src="/assets/img/student-of-the-year/award_header.jpg" class="img-responsive" alt="Student Award icon">
</div>


{% for item in page.dict %}
  <div class="col-md-4">
    <div class="student-container">
      <div class="student">
	{% if item.post %}
	    <h3><a href="{{ item.post }}">{{ item.student }}</a></h3>
	{% else %}
	    <h3>{{ item.student }}</h3>
	{% endif %}
      </div>
      <div class="year-offset">
	<h4>{{ item.year }}</h4>
      </div>
    </div>
  </div>
{% endfor %}
