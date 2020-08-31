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
* B.A. in Applied Mathematics (Highest Honors), UC Berkeley, May 2019. *Thesis: The Structure of the Sandpile Group*. *Advisor: Nikhil Srivastava*. 
* Ph.D in Computer Science, UT Austin. In Progress (Aug 2020-Present).

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

Work experience
======
* Mar 2020 - Aug 2020: Data Scientist, VergeSense
  * Built regression models to predict demand for office space using proprietary person-counting data

* Aug 2019 - Nov 2019: Software Engineer, WeWork. 
  * Deployed ensemble random forest model for predicting economic value of real estate acquisitions
  
Service and leadership
======
* Mathematics Department Peer Advisor, UC Berkeley, Aug 2018 - May 2019. 
