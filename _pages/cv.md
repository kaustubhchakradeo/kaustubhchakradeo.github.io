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
* Bachelor of Engineering in Information Technology, Pune University, 2019
* Master of Science in Artificial Intelligence, Radboud University, 2022
* Ph.D in Deep Learning for Medical Imaging, University of Copenhagen, 2025 (expected)

Work experience
======
* Research Intern at ScreenPoint Medical: June 2021 - September 2021
  * Project Title- Complete exploratory analysis of phases of respiration in 3D chest CT scans using Deep Learning
  * Working on classification of phases of respiration- inspiration and expiration from 3D chest CT scans to help in pulmonary disease detection
  * Used complete 3D volumes with variable depths with a 3D architecture. Used Explainable AI to corroborate the working of the model

* Research Intern (Thesis) at Thirona Bv: October 2021 - May 2022
  * Project Title- Assessing image quality in breast cancer mammography images using deep learning techniques
  * Developed a VGG-based Out of Distribution (OOD) model using PyTorch to create confidence scores for breast cancer mammography images. This model accepted breast images in correct orientations, and rejected images with bad positioning, wrong orientations, bad intensity and bad quality images including artefacts
  * Manually evaluated thirty thousand breast mammography images and classified them into different OOD classes
    
<!---Skills
======
* Main Language: Python- Numpy 
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3-->

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Posters
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
