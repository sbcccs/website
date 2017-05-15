---
layout: page
title: About
permalink: /about/
active: about
images:
  - image_path: /assets/img/about/slide1.jpg
    title:
  - image_path: /assets/img/about/slide2.jpg
    title:
  - image_path: /assets/img/about/slide3.jpg
    title:
  - image_path: /assets/img/about/slide4.jpg
    title:
  - image_path: /assets/img/about/slide5.jpg
    title:
  - image_path: /assets/img/about/slide6.jpg
    title:
  - image_path: /assets/img/about/slide7.jpg
    title:
  - image_path: /assets/img/about/slide8.jpg
    title:
  - image_path: /assets/img/about/slide9.jpg
    title:
  - image_path: /assets/img/about/slide10.jpg
    title:
  - image_path: /assets/img/about/slide11.jpg
    title:
  - image_path: /assets/img/about/slide12.jpg
    title:
---

<div class="aboutphotos">
    <h2 class="text before name text-center">
	Welcome to
    </h2>
    <h1 class="main name">Santa Barbara City College Computer Science</h1>
    {% for item in page.images %}
	<div class="col-lg-4 col-sm-6">
	    <a href="{{ item.url }}" class="home-page-photos-box">
		<img src="{{ item.image_path }}" class="img-responsive" alt="{{ item.title }}" />
		<div class="portfolio-box-caption">
		    <div class="portfolio-box-caption-content">
			<div class="title-category text-faded">
			    {{ item.title }}
			</div>
		    </div>
		</div>
	    </a>
	</div>
    {% endfor %}

</div>

<div class="about">
    <div class="row">
	<div class="box">
	    <div class="col-lg-12">
		<hr>
		    <h2 class="intro-text text-center"><strong>About</strong></h2>
		<hr>
	    </div>
	</div>
    </div>
</div>
We are in the Computer Age. Virtually every occupation in the world today has an interface with computers. From the microprocessor under the hood of your automobile to the larger scale systems used by Congress to formulate new laws, we are all affected in our daily lives by computers. Never before in history has any single endeavor grown so fast or become so universally accepted.

At Santa Barbara City College, we are helping students meet the challenges presented by this new technology. Classes, from introductory to advanced topics, are designed to provide general education, transfer and occupational training. The A.S. Degree requirements to follow are designed to prepare students for employment or transfer to both the CSU and UC systems.
