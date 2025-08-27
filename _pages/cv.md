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
* Ph.D in Computer Science, University of Luxembourg, 2028 (expected)
* M.S. in Computer Science and Engineering, Technical University of Denmark, 2021
* B.S. in Software Technology, Technical University of Denmark, 2018

Work experience
======
* 2022 - 2024: Software Engineer
  * Mobile Industrial Robots
  * Team: Navigation, R&D
  * Duties includes: Software architecture and development

* 2018 - 2021: Student Assistant Software Developer
  * Robotize
  * Duties included: Development of auxiliary products
  
Skills
======
* Experience with C++, Python, Java, C# programming
* Logical and mathematical proofs
* Design automatic proofs using proof assistants such as Isabelle
* LaTeX
* Proficient with Unix systems such as Linux
* Regular use of Git

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
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
