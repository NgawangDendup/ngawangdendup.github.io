---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
header:
  og_image: "research/ecdf.png"
---
Academic Year 2022 -
=====
- Statistics II
- Advanced Econometrics
- Basic Seminar
- Statistics for Causal Inference (Intermediate Seminar)
- Applied Microeconometrics

Academic Year 2019 - 2021
========
- Applied Microeconometrics (graduate level) 
- Advanced Econometrics (undergraduatel level)

Teaching Philosophy
===================
- Explaining learning objectives clearly
- Learning is two way process
- Clearly explaining concepts and terminlogy
- Getting our hands dirty is must for maximizing our learning experience
- Always remain accessible to students
- Life long learning
- Global citizen

Teaching Experiences (others)
===================
- RA Microeconomics I (PG level) and Econometrics I (PG level) at Waseda University
- Royal University of Bhutan: Microeconomics, Macroeconomics, Statistics, Development Economics

Others
======
If you are interested in the courses that I offer at Waseda, but you are not a regular student of Waseda University, please write to me. I will be more than happy to guide you or share my teaching materials. 

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
