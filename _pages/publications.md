---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<a href="https://www.researchgate.net/profile/Kaustubh-Chakradeo/publication/349644405_Malaria_Parasite_Detection_Using_Deep_Learning_Methods/links/6050bafa458515e8344e3deb/Malaria-Parasite-Detection-Using-Deep-Learning-Methods.pdf" target="_blank">Malaria Parasite Detection Using Deep Learning Methods</a> **Chakradeo Kaustubh**, Delves Michael, Titarenko Sofya.

<a href="https://ieeexplore.ieee.org/abstract/document/9066248/" target="blank"> Breast cancer recurrence prediction using machine learning</a>  **Chakradeo Kaustubh**, Vyawahare Sanyog, Pawar Pranav.

<a href="https://ieeexplore.ieee.org/abstract/document/9318672/" target="blank"> Chatbot assistant for English as a second language learners </a> Vyawahare Sanyog, **Chakradeo Kaustubh**

<a href="https://ieeexplore.ieee.org/abstract/document/10414062/" target="blank"> Real-time Plant Disease Dataset Development and Detection of Plant Disease Using Deep Learning </a> Joseph Diana, Pawar Pranav, **Chakradeo Kaustubh.**

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
