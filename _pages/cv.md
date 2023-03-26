---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[PDF Version of CV](https://nmaterise.github.io/files/nrm_cv_abbrv_230222.pdf)

Education
======
* B.S. in Electrical Engineering & Physics, Northeastern University, 2016
* PhD in Applied Physics, Colorado School of Mines, 2023 (expected)

Research Experience
======
* 08/2018--Present, Graduate Research Assistant, Colorado School of Mines
* 01/2021--Present, Affiliate Researcher, NIST Boulder
* 08/2018--Present, Indeterminate Status Employee, LLNL
* 06/2016--08/2018, Computer Scientist, LLNL
* 07/2015--12/2015, Materials Science Co-op Student, LLNL
* 03/2014--03/2015, Research Assistant, Northeastern University
* 07/2013--12/2013, Quantum Information Co-op Student, Raytheon BBN Technologies
* 06/2012--12/2012, REU Student, Northeastern University

Skills
======
* Programming languages: Python, Julia, C/C++, OpenCL/CUDA, VHDL
* Finite element software: Ansys, COMSOL
* Microwave instruments: vector network analyzers, spectrum analyzers,
  oscilloscopes 
* Microwave electronics packaging: manual/automatic wire bonding, soldering
* Cryogenic systems: dilution refrigerators, adiabatic demagnetization
  refrigerators
  
Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Patents
======
  <ul>{% for post in site.patents reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Posters
======
  <ul>{% for post in site.posters reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
<!---
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
-->
