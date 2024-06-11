---
layout: archive
title: " "
permalink: /teaching/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

Academic Year 2024
=====
- Statistics I and II (using R and RStudio)

Academic Year 2023 
=====
- Applied Microeconometrics (graduate level)
- Statistics I and II (using R and RStudio)
- Undergraduate Basic Seminar

Academic Year 2022 
=====
- Applied Microeconometrics (graduate level)
- Statistics II (using R and RStudio)
- Advanced Econometrics
- Basic Seminar
- Statistics for Causal Inference (Intermediate Seminar)

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
- Royal University of Bhutan: Microeconomics, Macroeconomics, Statistics, Development Economics

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
