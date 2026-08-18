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
  * Topic: graph-based machine learning for power system operation
  * Supervisor: Dr. Jochen Cremer
* M.S. in Electrical and Computer Engineering, Carnegie Mellon University, 2022

Research experience
======
* 2023–present: PhD researcher, Delft AI Energy Lab, TU Delft
  * Graph neural networks for AC optimal power flow, machine learning surrogates for time-domain/EMT simulation, learning-accelerated stochastic scheduling
* 2022: Research intern (CaCTüS programme), RoLi Lab, Max Planck Institute for Biological Cybernetics, Tübingen, Germany
  * Improved the real-time tracking algorithm of the first freely swimming larval zebrafish tracking microscope

Skills
======
* Machine learning: PyTorch, PyTorch Geometric, graph neural networks, physics-informed learning
* Programming: Python, MATLAB, Git
* Power systems: power flow and optimal power flow, EMT/time-domain simulation, dynamic security assessment

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
