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
======
* B Tech in Electrical Engineering, Indian Institute of Technology Roorkee, 2011
* M.S. in Computer Science, KTH Royal Institute of University, Stockholm 2017
* Ph.D in Computational Science, Aalto University, 2021 (expected)

Work experience
======
* 2018-2018: Research Scientist Intern-Amazon Cambridge
  * GP Models
  * Read about Supply Chain Optimisation Automation using Reinforcement Learning


* 2012-2013: Lead Engineer -InfoEdge
  * Building ML pipeline and internal algorithms to improve search and recommendation
  * Technology: SOLR, Python, JAVA


* 2011-2012: Software Engineer-PayU
  * contributed to building payment gateway
  * Technology: PHP, MySQL, Bootstrap.js

Skills
======
* Python
* MATLAB, C++
* PHP, MySQL, MongoDB


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
