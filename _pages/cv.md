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
* MPhys Computational Physics, 1st class, University of Edinburgh 2016-2021
* Ph.D applied mathematics, University of Edinburgh, 2021 - ongoing

Technical Skills
======
* Programming Experience:
    * Machine learning and differentiable programming
    * Numerical methods and simulation techniques (Agent based models, monte-carlo methods)
    * Graph optimisation
    * Image processing
    * GPU and MPI parallelisation
* Software and Tools:
    * Python (JAX, PyTorch, numpy, scipy, matplotlib, tensorflow, pandas)
    * Bash
    * Kubernetes
    * ImageJ
    * C, C++, MATLAB, Cuda
* Mathematics:
    * Partial differential equations and dynamical systems
    * Statistical mechanics and probability theory
    * Mathematical modelling

Academic Experience
======
* Research:
    * Modelling spatio-temporal pattern formation with Neural Cellular Automata (see Projects page).
    * Predicting hospital ICU stay times with patient demographics and disease co-occurrences via graph clustering algorithms.
    * Validating the performance of wind turbines after modifications, given noisy/unreliable direct measurement.
    * Ongoing work exploring how to fit reaction-diffusion-advection equations to biological data.
* Other experience:
    * I run a weekly reading group for scientific applications of machine learning, which involves organising/giving talks, and discussing papers as a group.
    * Attended a wide range of conferences (see Conferences page), sometimes presenting my work, which has led to ongoing collaborations.
    * Experience presenting technical work in a clear and understandable manner.
    * Experience working in a team and independently, balancing the time commitments of several concurrent projects.
    * Cosupervised 2 Masters dissertations on the evolution of intelligence in biologically inspired systems.

Work experience
======
* Summer 2019 - Research assistant
    * Assisted a PhD student with research in frustrated anti-ferromagnets
    * Developed C++ code to simulate the classical heisenberg model

* 2017 - 2020 - Maths and Physics tutor
    * Part time tutoring of high school level maths and physics
* 2021 - ongoing - Teaching assistant
    * Teaching assistant for undergraduate scientific programming courses, giving me experience in debugging other people's code and explaining technical concepts to those who don't understand them.

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Conferences
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  


