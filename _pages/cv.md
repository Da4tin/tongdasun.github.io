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
* Ph.D in Data Science, City University of Hong Kong, 2026 (expected)
* M.Eng. in Mechanical Engineering, Harbin Institute of Technology, 2022
* B.Eng. in Mechanical Engineering, Chongqing University, 2019

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Fields
======
* Machine Fault Diagnosis & Prognosis
* Few-Shot Learning
* Multivariate Time Series Modeling
* Industrial LLM
  
Skills
======
* ** Programming Language: **Python, R, C/C++

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
  
