---
layout: cv
title: Matej Kala
subtitle: Software Developer, Organic Chemist
description: 
#quote: Work smart
email: kalamatej@gmail.com
home: www.matejkala.com
github: github.com/ka1amita
linkedin: www.linkedin.com/in/matej-kala
address: Prague, Czech Republic
phone: +420 737 239 310
marital-status: single
citizenship: Czech Republic

photo: matejkala.png
include-currently: false
include-outline: false
include-responsibilities: false
include-achievements: false
#length: long
---

{% if page.photo %}
<img id="photo" src="{{ page.photo | prepend: '/assets/photo/' | relative_url }}" alt="Matej Kala">
{% endif %}

# {{page.title}}

{{page.subtitle}}

<ul id="web-address">
<li><i class="fa-solid fa-house-laptop"></i><a aria-label="homepage" target="_blank" href="https://{{ page.home }}">{{ page.home }}</a></li>
<li><i class="fa-brands fa-github"></i><a aria-label="GitHub" target="_blank" href="https://{{ page.github }}">{{ page.github }}</a></li>
<li><i class="fa-brands fa-linkedin"></i><a aria-label="LinkedIn" target="_blank" href="https://{{ page.linkedin }}">{{ page.linkedin }}</a></li>
{% if page.marital-status %}
<li><i class="fa-solid fa-ring"></i><span aria-label="marital status">{{ page.marital-status }}</span></li>
{% endif %}
{% if page.citizenship %}
<li><i class="fa-solid fa-passport"></i><span aria-label="citizenship">{{ page.citizenship }}</span></li>
{% endif %}
{% if page.address %}
<li><i class="fa-solid fa-home"></i><a aria-label="address" target="_blank" href="https://en.mapy.cz/turisticka?q={{ page.address | cgi_escape }}">{{ page.address }}</a></li>
{% endif %}
<li><i class="fa-solid fa-phone"></i><a aria-label="phone" target="_blank" href="tel:{{ page.phone | replace: ' ', ''  }}">{{  page.phone }}</a></li>
<li><i class="fa-solid fa-at"></i><a aria-label="e-mail" target="_blank" href="mailto:{{ page.email }}">{{ page.email }}</a></li>
</ul>

{% if page.quote %}
> {{ page.quote }}
{% endif %}

{% if page.include-currently %}
## Currently

I recently took a leave to get the education needed to start my new career.
It was amazing to gain so much new knowledge. But I'm not going to end here.
I have a strong desire to improve my skills and further expand my knowledge to excel in the new job.
{% endif %}

## Tech Stack

+ <i class="fa-solid fa-star"></i>Java
  ![java](assets/icons/java.svg)
+ <i class="fa-solid fa-star-half-stroke"></i>Python
  ![python](assets/icons/python.svg)
+ <i class="fa-solid fa-star"></i>SpringBoot
  ![spring](assets/icons/spring.svg)
+ <i class="fa-solid fa-star-half-stroke"></i>Flyway
  ![flyway](assets/icons/flyway.svg)
+ <i class="fa-solid fa-star-half-stroke"></i>Docker
  ![docker](assets/icons/docker.svg)
+ <i class="fa-solid fa-star-half-stroke"></i>AWS
  ![ec2](assets/icons/ec2.svg)
+ <i class="fa-regular fa-star"></i>Terraform
  ![terraform](assets/icons/terraform.svg)
+ <i class="fa-solid fa-star"></i>CircleCI
  ![circleci](assets/icons/circleci.svg)
+ <i class="fa-solid fa-star-half-stroke"></i>SQL
  ![mysql](assets/icons/mysql.svg)
+ <i class="fa-solid fa-star"></i>Git
  ![git](assets/icons/git.svg)

[//]: # (<i class="fa-solid fa-star"></i>)
[//]: # (<i class="fa-solid fa-star-half-stroke"></i>)
[//]: # (<i class="fa-regular fa-star"></i>)

### Soft Skills

+ ![team](assets/icons/team.svg)
  Teamwork
+ ![search](assets/icons/search.svg)
  Attention to Detail
+ ![ear](assets/icons/ear.svg)
  Curiosity
+ ![bulb](assets/icons/bulb.svg)
  Problem Solving

### Interests

+ ![chatgpt](assets/icons/chatgpt.svg)
  ChatGPT
+ ![chart](assets/icons/chart.svg)
  Data Science
+ ![farmer](assets/icons/farmer.svg)
  Volunteering
  [![certificate](assets/icons/certificate.svg)](assets/certs/230904-caritas-bergeinsatz-nachweis.pdf)
+ ![teacher](assets/icons/teacher.svg)
  Teaching in a [climbing club](https://www.vsak.net/)

## Languages

+ ![united-kingdom](assets/icons/united-kingdom.svg) English - full professional proficiency
+ ![germany](assets/icons/germany.svg) German - intermediate
  [![certificate](assets/icons/certificate.svg)](assets/certs/deutsch-a2.pdf)
+ ![czechia](assets/icons/czechia.svg) Czech - native

## Experience

`2023 - now`
**Professional Development**
,
Career Break

{% if page.include-outline %}
<h3> </h3>

I took a leave to gain the knowledge needed to start my new career in IT.
It was amazing to gain so much new information. But I'm not going to end here.
I have a strong desire to improve my skills and further expand my knowledge to excel in the new job.
{% endif %}

<h2> </h2>

`2023`
**Process Research Chemist**
,
_[Teva](https://www.teva.cz/)_,
Opava, Czech Republic
![czechia](assets/icons/czechia.svg)

{% if page.include-outline %}

### Outline

Member of a process research team developing API manufacturing processes.

{% endif %}

<h2> </h2>

`2020-2022`
**Process Research Chemist**
[![certificate](assets/icons/certificate.svg)](assets/certs/syngenta-certificate.pdf),
_[Syngenta](https://www.syngenta.com/)_,
Stein (AG), Switzerland
![switzerland](assets/icons/switzerland.svg)

{% if page.include-outline %}
### Outline

Member of a small process R&D team developing scalable, safe and cost-efficient processes 
transferred to kilo-lab 
and investigating broad range of alternative pathways for patenting purposes 
or a future development.
{% endif %}

{% if page.include-responsibilities %}
### Responsibilities

Skillful planning and execution of multistep organic synthesis using a range of synthetic techniques 
(including e.g. microwave chemistry and photochemistry) on sub-mmol to mol scale.

  {% if page.length == 'long' %}
Thorough planning and attention to detail while executing sensitive reactions 
(e.g. Schlenk techniques, drying and degassing of solvents,
work-up screening to avoid product decomposition).

Quantification (by qNMR or LC-UV in combination with statistical analysis) of investigated
reactions
and sensitive reagents with high degree of precision and accuracy.

Separation (using preparative Flash, TLC or RP-HPLC) and identification 
(using LC-MS, GC-MS with 1D and 2D NMR spectroscopy) 
of unknown side-products in proposed speculative reactions.

Optimization ranging from simple solvent screening (using published PCA or cluster analysis data)
to multi-parameter optimization (using DoE).
Conducting and analysing a dozen reactions simultaneously.

Understanding laws of physical chemistry, 
reaction kinetics and reactivity hazards backed up by literature sources 
and hazard evaluation techniques (DSC) in order to conduct reactions in a safe manner.

Supporting young team members.
  {% endif %}
{% endif %}

{% if page.include-achievements %}
### Achievements

Participation in a project awarded with a company award.

Planning, execution and analysis of a multi-parameter optimization using DoE
resulting in development of superior conditions giving very high enantioselectivity
while decreasing expensive ligand and catalyst loadings.

  {% if page.length == 'long' %}
Implementation of innovative reactions based on own ideas 
(new method for amidine synthesis or C-N coupling by Ag(I) or Cu(I)).
  {% endif %}
{% endif %}

<h2> </h2>

`2016-2019`
**Process Research Team Leader**
,
_[Farmak](https://www.farmak.cz/)_,
Olomouc, Czech Republic
![czechia](assets/icons/czechia.svg)

{% if page.include-outline %}
### Outline

Development of multi-stage API production processes - from the laboratory route development and
optimization through scale-up on 15 liters glass reactors to transfer of the final process to the
pilot-plant for validation.
{% endif %}

{% if page.include-achievements %}
### Achievements

As a chief project researcher, successfully transferred one project for validation.

Dealt with the optimization of non-reproducible lithiation resulting in highly robust process.

Solved oiling-out problems during key crystallization of API intermediate.
{% endif %}

## Education

`2008-2013`
**Master's degree in Organic Chemistry**
[![certificate](assets/icons/certificate.svg)](assets/certs/msc-diploma.pdf) [![certificate](assets/icons/certificate.svg)](assets/certs/bc-diploma.pdf),
_[University of Chemistry and Technology](https://www.vscht.cz/?jazyk=en)_,
Prague, Czech Republic
![czechia](assets/icons/czechia.svg)
{% if page.length == 'long' %}

<h2> </h2>

`2013-2016`
**unfinished doctorate in Organic Chemistry**
,
_[University of Chemistry and Technology](https://www.vscht.cz/?jazyk=en)_,
Prague, Czech Republic
![czechia](assets/icons/czechia.svg)
{% endif %}

### Courses

`2023`
**Junior Software Developer**
[![certificate](assets/icons/certificate.svg)](assets/certs/green-fox-academy-certificate.pdf),
_[Bootcamp](https://www.greenfoxacademy.com/en/home),_
Online
![internet.svg](assets/icons/internet.svg)

<h2> </h2>

**Python 3**
[![certificate](assets/icons/certificate.svg)](assets/certs/codecademy-certificate.pdf),
_[Codecademy](https://www.codecademy.com)_

<h2> </h2>

**Data Analyst**
[![certificate](assets/icons/certificate.svg)](assets/certs/codecademy-certificate.pdf),
_[Codecademy](https://www.codecademy.com)_

<!-- ### Footer

Last updated: December 2023 -->
