---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
Find my CV attached below. 
[CV (PDF)]({{ '/files/CV.pdf' | relative_url }})


## Education
* BSc. Combined Honours Math and Computer Science, University of British Columbia, 2026


## Publications
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

