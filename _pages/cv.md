---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Currently in progress!

Education
======
* Ph.D in Biophysics, Stanford University, 2021
* MPhil in Physics, University of Cambridge, 2014
* A.B. in Chemical and Physical Biology, _summa cum laude_, Harvard College, 2013

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-pubs.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Outreach
======
  <ul>{% for post in site.outreach reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

  * 2015-2018: Co-founder and COO, 
     [Stanford Future Advancers of Science and Technology](https://fast.stanford.edu)
  * 2014-2017: Mentor, Ask-A-Scientist, Escondido Elementary, Stanford CA
