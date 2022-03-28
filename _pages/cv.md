---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Work
======
Research Fellow, Centre for Electronic Frontiers, University of Southampton

Previously:
* Research Assistant, [Microsystems Group](https://www.ncl.ac.uk/engineering/research/electrical-electronic-engineering/u-systems/), Newcastle University
* Research Intern, Arm
  
Education
======
* PhD, Newcastle University, 2021
  * Low Power and Asynchronous Design for Machine Learning
* MEng, University of Southampton, 2016
  * Electronic Engineering with Computer Systems

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
  
{% comment %}

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
{% endcomment %}
