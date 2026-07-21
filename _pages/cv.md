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
* Ph.D in Astrophysics, School of Physics, Peking University, 2028 (expected)
* B.S. (honours degree) in Astronomy, School of Physics, Peking University, 2023

Research Interests
======
* Pulsar magnetospheres: theories and observations
* Coherent emission processes
* Plasma
  
Skills
======
* Physical modeling
* Radio pulsar data reduction & analysis
* Particle-in-Cell simulation

Publications
======
  Below are my first-author papers. For a full publication list, please refer to ORCID on the left.
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Selected Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Hobby
======
* Guitar
* Music
* Comics
