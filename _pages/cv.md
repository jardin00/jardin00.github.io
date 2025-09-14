---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<!--{% include base_path %}-->

<div class="cv-download-links" style="margin:1rem 0;">
  <!-- 다운로드 버튼 -->
  <a href="{{ '/files/cv_github.pdf' | relative_url }}" class="btn btn--primary" target="_blank">
    Download CV as PDF
  </a>
</div>

<!-- PDF 임베드 -->
<div style="position:relative; width:100%; height:0; padding-bottom:141.4%; max-height:100vh; margin:1rem 0;">
  <iframe 
    src="{{ '/files/cv_github.pdf' | relative_url }}#zoom=page-fit"
    title="CV PDF Preview"
    style="position:absolute; inset:0; width:100%; height:100%; border:none;">
  </iframe>
</div>


<!--
Education
======
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)
* M.S. in Jekyll, GitHub University, 2014
* B.S. in GitHub, GitHub University, 2012

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
>
