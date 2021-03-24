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
* Bsc Computer Science, Sharif University of Technology, Tehran, Iran.


Work experience
======
* Summer 2019: Research Internship
  * Ruhr University of Bochum (RUB)
  * Design and implement software level countermeasures against hardware fault attack on ARMv6m.
  * Supervisor: Professor Amir Moradi

* February 2020 - August 2021 : Scientific intern
  * Institute of Science and Technology Austria (IST Austria)
  * Design of decoding algorithm for Reed-Muller Codes.
  * Supervisor: Professor Marco Mondelli


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
