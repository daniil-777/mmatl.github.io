---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
------
* Current EECS Ph.D student in Robotics and Control, UC Berkeley, 2021 (expected)
  * Winner of National Defense Science and Engineering Graduate Fellowship (NDSEG), 2017-2021
* B.S.E in Electrical Engineering, Princeton University, 2016
  * GPA: 3.97
  * Minor in Computer Science
  * Winner of the [James Hayes-Edgar Palmer Prize in Engineering](http://ee.princeton.edu/news/two-ee-seniors-receive-seas-undergraduate-awards-0)

Publications
------
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
------
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Work Experience
------
* AppNexus (June - August 2015), _New York, NY_
  * Real-Time Distributed Systems Engineer

* Brewster, Inc. (June - September 2014), _New York, NY_
  * Web Engineer

* Infosys (June - August 2013), _Bangalore, India_
  * Cloud Dependability Research Intern
