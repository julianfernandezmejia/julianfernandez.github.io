---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

My full CV is available in PDF: **[Download CV (PDF)](https://raw.githubusercontent.com/julianfernandezmejia/Archivos/b5d1435a8446b0dd2aa722910d8c4d6579c1d0bf/CV%20-%20Webpage.pdf)**

Education
======
* Ph.D. in Economics, Copenhagen Business School (CBS), 2024
* Assistant Professor of Finance, Universidad Javeriana - Bogotá

Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Talks
======
<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

Teaching
======
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
