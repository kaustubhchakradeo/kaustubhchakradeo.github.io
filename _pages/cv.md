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
* June 2021 - September 2021: Research Intern
  * ScreenPoint Medical
  * Duties included: Developing an Out of Distribution model to create automated confidence scores for breast cancer mammography images as a part of quality control.  

*  October 2021 - May 2022: Research Intern (Thesis)
  * Thirona Bv
  * Duties included: Developing a deep learning model for classifying phases of respiration- inspiration and expiration from 3D chest CT scans to help in pulmonary disease detection
    
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
  
