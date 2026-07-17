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
* B.S. in Astronomy, School of Physics, Peking University, 2023
  
Skills
======
* Physical modeling
* Radio pulsar data reduction & analysis
* Particle-in-Cell simulation

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
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
