---
layout: cv
title: Matej Kala
subtitle: Software Developer
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
include-currently: true
include-outline: true
include-responsibilities: false
include-achievements: true
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

I am a Java backend developer with almost 2 years of experience with the development of backend applications for Czech government agencies.

I have passion for the field and strong desire to keep learning new things.

I'm particularly drawn to engineering practices that ensure code quality and maintainability:
Test-Driven Development, Domain-Driven Design and automation of testing, deployment, and quality checks.

{% endif %}

## Skills

+ ![team](assets/icons/car.svg)
  Driving Licence - B
+ ![team](assets/icons/team.svg)
  Teamwork
+ ![search](assets/icons/search.svg)
  Attention to Detail
+ ![ear](assets/icons/ear.svg)
  Curiosity
+ ![bulb](assets/icons/bulb.svg)
  Problem Solving

### Tech Stack

+ <i class="fa-solid fa-star"></i>Java ![java](assets/icons/java.svg)
+ <i class="fa-solid fa-star-half-stroke"></i>SQL ![mysql](assets/icons/sql.svg)
+ <i class="fa-regular fa-star"></i>Python ![python](assets/icons/python.svg)
+ <i class="fa-regular fa-star"></i>Java Script ![java-script](assets/icons/java-script.svg)
+ <i class="fa-solid fa-star-half-stroke"></i>Open API ![open-api](assets/icons/open-api.png)
+ <i class="fa-solid fa-star"></i>Spring ![spring](assets/icons/spring.svg)
+ <i class="fa-solid fa-star"></i>Spring Boot ![spring-boot](assets/icons/spring-boot.svg)
+ <i class="fa-solid fa-star-half-stroke"></i>Hibernate ![hibernate](assets/icons/hibernate.svg)
+ <i class="fa-solid fa-star"></i>JUnit 5 ![junit-5](assets/icons/junit-5.svg)
+ <i class="fa-regular fa-star"></i>React ![react](assets/icons/react.svg)
+ <i class="fa-solid fa-star-half-stroke"></i>Kafka ![kafka](assets/icons/kafka.svg)
+ <i class="fa-solid fa-star-half-stroke"></i>Solr ![solr](assets/icons/solr.svg)
+ <i class="fa-solid fa-star-half-stroke"></i>Gradle ![gradle](assets/icons/gradle.svg)
+ <i class="fa-regular fa-star"></i>Maven ![maven](assets/icons/maven.svg)
+ <i class="fa-solid fa-star-half-stroke"></i>Docker ![docker](assets/icons/docker.svg)
+ <i class="fa-solid fa-star"></i>Git ![git](assets/icons/git.svg)
+ <i class="fa-regular fa-star"></i>Subversion ![subversion](assets/icons/subversion.svg)
+ <i class="fa-solid fa-star"></i>IDEA ![idea](assets/icons/idea.svg)

## Languages

+ ![united-kingdom](assets/icons/united-kingdom.svg) English - full professional proficiency
+ ![germany](assets/icons/germany.svg) German - intermediate
  [![certificate](assets/icons/certificate.svg)](assets/certs/deutsch-a2.pdf)
+ ![czechia](assets/icons/czechia.svg) Czech - native

## Experience

<h3> </h3>

`Feb 2024 - now`
**Software Developer**
,
_[OKsystem](https://www.oksystem.com)_,
Prague, Czech Republic
![czechia](assets/icons/czechia.svg)

{% if page.include-outline %}

### Outline

Member of a cross-functional team developing and maintaining two backend applications.
One legacy monolithic application power by _Maven_, _Java_ 8 and _Spring_ 4.
And one brand new microservice-based application power by _Gradle_, _Java_ 21 and _Spring Boot_ 3.

Adding features mostly spanning _HTTP_ (_REST_) communication, _Kafka_ messaging, database _CRUD_ operations
and scheduling tasks.

{% endif %}

{% if page.include-responsibilities %}

### Responsibilities

Unit and integration testing of the developed features.

Configure and populate _Solr_ cores for full-text search capabilities.

Deployment of the legacy application to integration environment.

{% endif %}

<h3> </h3>

`2023 - 2024`
**Professional Development**
,
Career Break

<h3> </h3>

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

<h3> </h3>

`2020 - 2022`
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

<h3> </h3>

`2016 - 2019`
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

<h3> </h3>

`2008 - 2013`
**Master's degree in Organic Chemistry**
[![certificate](assets/icons/certificate.svg)](assets/certs/msc-diploma.pdf) [![certificate](assets/icons/certificate.svg)](assets/certs/bc-diploma.pdf),
_[University of Chemistry and Technology](https://www.vscht.cz/?jazyk=en)_,
Prague, Czech Republic
![czechia](assets/icons/czechia.svg)

{% if page.length == 'long' %}

<h3> </h3>

`2013 - 2016`
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

<h3> </h3>

**Python 3**
[![certificate](assets/icons/certificate.svg)](assets/certs/codecademy-certificate.pdf),
_[Codecademy](https://www.codecademy.com)_

<h3> </h3>

**Data Analyst**
[![certificate](assets/icons/certificate.svg)](assets/certs/codecademy-certificate.pdf),
_[Codecademy](https://www.codecademy.com)_

## Interests

+ ![chart](assets/icons/chart.svg) Data Science
+ ![farmer](assets/icons/farmer.svg) Volunteering [![certificate](assets/icons/certificate.svg)](assets/certs/230904-caritas-bergeinsatz-nachweis.pdf)
+ ![orienteering](assets/icons/orienteering.svg) Orienteering
+ ![teacher](assets/icons/teacher.svg) Teaching in a [climbing club](https://www.vsak.net/)