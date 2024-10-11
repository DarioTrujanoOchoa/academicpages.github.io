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
* Ph.D. student in Economics, UCSB, 2025 (expected)
* M.S. in Economics, CIDE, 2017
* B.S. in Psychology, UNAM, 2013
  

[//]: # (Work experience)

[//]: # (======)

[//]: # (* Summer 2015: Research Assistant)

[//]: # (  * Github University)

[//]: # (  * Duties included: Tagging issues)

[//]: # (  * Supervisor: Professor Git)

[//]: # ()
[//]: # (* Fall 2015: Research Assistant)

[//]: # (  * Github University)

[//]: # (  * Duties included: Merging pull requests)

[//]: # (  * Supervisor: Professor Hub)
  
Talks
======

  <ul>
    {% for post in site.talks reversed %}
      {% include archive-single-talk-cv.html %}
    {% endfor %}</ul>
  
Teaching
======
<ul>
    {% for post in site.teaching %}
        {% include archive-single-cv.html %}
    {% endfor %}
</ul>

Skills
======
* English: Fluent
* Spanish: Native
* Skateboarding for commuting
* Cumbia Dancing
* R Programming: tidyverse and ggplot2
* Software to implement experiments:
  * Otree
  * Qualtrics
  * Prolific

Publications
======
  <ul>
    {% for post in site.publications reversed %}
      {% include archive-single-cv.html %}
    {% endfor %}
  </ul>

<embed src="https://dariotrujanoochoa.github.io/files/CV_eng.pdf" type="application/pdf" width="100%" />
