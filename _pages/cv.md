---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download my academic CV (PDF)]({{ '/files/Mingjia_Shi_CV.pdf' | relative_url }})

Education
======
<!-- * Ph.D in Version Control Theory, GitHub University, 2018 (expected) -->
* Ph.D candidate in University of Virginia, 2025-
* M.E. in Sichuan University University, 2021-2024
* B.E. in Sichuan University University, 2015-2019

Work experience
======
<!-- * Summer 2024: Intern Researcher
  * Shanghai AI Lab
  * Duties includes: Multimodal LLM and Token efficiency
  * Supervisor: Kaipeng Zhang  -->

* May-August 2026: AI Research & Development Intern
  * Nokia, Sunnyvale, California, United States (on-site)
  * Research focus: long-context compression and robustness.

* Winter 2025: Intern Researcher
  * HoumoAI
  * DUties includes: Research on Resource Preserving Data Application

* Winter 2023: Intern Researcher
  <!-- * Lenovo AI Reasearch in Beijing -->
  * Lenovo Reasearch in Beijing
  <!-- * Duties includes: Research on  Federated Learning and Videos Analysis -->
  * Duties includes: Research on Resource Preserving Data Application, Decentralized Data Analyses

* Winter 2022: Intern Student
  * NUS HPC Lab
  <!-- * NUS HPC-AI Lab -->
  * Duties includes: Research on Resource Preserving Data Application

* Summer 2018: Intern Researcher
  * Lenovo Reasearch in Chengdu
  * Duties included: Decentralized Data Analyses
  
<!-- Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3 -->

Publications
======
{% assign dated_publications = site.publications | sort: 'date' | reverse %}
{% assign publication_groups = '0,1,2' | split: ',' %}
{% for group in publication_groups %}
  {% assign priority = group | plus: 0 %}
  {% if priority == 0 %}<h2>First-Author / Co-First-Author Papers</h2>{% endif %}
  {% if priority == 1 %}<h2>Co-Authored Papers</h2>{% endif %}
  <ul>
  {% for post in dated_publications %}
    {% if post.author_priority == priority %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}
  </ul>
{% endfor %}

  
<!-- Talks
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
* Currently signed in to 43 different slack teams -->
