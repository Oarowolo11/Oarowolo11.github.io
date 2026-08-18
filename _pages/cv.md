---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="{{ base_path }}/files/Olayiwola_Arowolo_CV.pdf" class="btn btn--primary">Download CV (PDF)</a>

Education
======
* Ph.D. in Electrical Engineering, Delft University of Technology, 2023–present (final year)
  * Intelligent Electrical Power Grids group, Delft AI Energy Lab
  * Topic: Generalisation of Machine Learning Models for Power Systems Applications
  * Supervisor: Dr. Jochen Cremer
* M.S. in Electrical and Computer Engineering, Carnegie Mellon University, 2022
* B.Sc. in Electrical and Electronic Engineering, University of Ibadan, 2020

Experience
======
* 2023–present: PhD researcher, Delft AI Energy Lab, TU Delft, the Netherlands
* 2024–2026: Teaching Assistant, Machine Learning Workflows for Digital Energy Systems, TU Delft, the Netherlands
* Oct–Dec 2022: Teaching Assistant, College of Engineering, Carnegie Mellon University, Kigali, Rwanda
* Jul–Sep 2022: Machine Learning Intern (CaCTüS programme), RoLi Lab, Max Planck Institute for Biological Cybernetics, Tübingen, Germany
* May–Jul 2022: Data Science Intern, Plentify, Cape Town, South Africa
* May–Jul 2021: Engineering Graduate Trainee, Elektron Energy, Lagos, Nigeria
* 2020–2021: Data Science Instructor, Robotics and Artificial Intelligence Nigeria, Ibadan, Nigeria

Skills
======
* Machine learning: PyTorch, PyTorch Geometric, Graph neural networks, Physics-informed learning
* Programming: Python, MATLAB, Git
* Power Systems: Power flow and optimal power flow, time-domain simulation, dynamic security assessment

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
