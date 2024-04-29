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
<ul>{% for post in site.education reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Research experiences
======
  <ul>{% for post in site.researches reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Skills
======
* **Languages:** English (Proficient in reading and writing and Fluent in speaking) Mandarin Chinese (Native).
* **Coding:** Python, Matlab, C++, C, LabVIEW, LaTeX typesetting, Markdown, …
* **Software:** SolidWorks, Abaqus, Anasys, Multisim, Proteus, Origin, …
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Referee
======
* Currently signed in to 43 different slack teams
