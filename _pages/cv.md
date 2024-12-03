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
* B.S. in Automation, Anhui University, 2013-2017
* M.S. in Control Science and Control Engeneering, Southeast University, 2017-2020
* Ph.D in Control Science and Control Engeneering, Zhejiang University, 2020-2024 (expected)

Exchange
======
* 2023.02 - 2023.08:  Joint PhD student, ETH Zurich
  * ETH Zurich, Switzerland
  * Working on distributed adaptive minimax optimization in Optimization and Decision Intelligence (ODI) group
  * Supervisor: Niao He


Publications
======
  <ul>{% for post in site.publications reversed %}
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
  
