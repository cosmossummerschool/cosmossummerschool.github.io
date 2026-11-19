---
layout: page
title: Instructors
nav_order: 3
description: A listing of all the course staff members.
---

## Organizers

{% assign organizers = site.instructors | where: 'role', 'Organizer1' %}
{% for staffer in organizers %}
{{ staffer }}
{% endfor %}

{% assign organizers = site.instructors | where: 'role', 'Organizer2' %}
{% for staffer in organizers %}
{{ staffer }}
{% endfor %}

{% assign organizers = site.instructors | where: 'role', 'Organizer3' %}
{% for staffer in organizers %}
{{ staffer }}
{% endfor %}
## Keynote
Coming soon!
{% assign keynote = site.instructors | where: 'role', 'Keynote' %}
{% for staffer in keynote %}
{{ staffer }}
{% endfor %}

## Instructors
Coming soon!
{% assign instructors = site.instructors | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.instructors | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}

## Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}


## Previous years

### COSMOS 2025
* Keynote: [Tatsuya Kameda](http://www.tatsuyakameda.com/homeeng.html){:target="_blank"} (Meiji Gakuin University)
* [Damien Farine](https://sites.google.com/site/drfarine/home){:target="_blank"} (Australian National University)
* [Joseph Austerweil](https://alab.psych.wisc.edu/){:target="_blank"} (Chiba Tech)
* [Lio Wong](https://web.mit.edu/zyzzyva/www/academic.html){:target="_blank"} (Stanford)
* [Lucy Aplin](https://sites.google.com/site/lucymaplin/home){:target="_blank"} (Australian National University)
* [Lusha Zhu](https://www.lushazhu.com/){:target="_blank"} (Peking University)
* [Mayuko Nakamaru](https://sites.google.com/view/mayukonakamarulab/%E3%83%9B%E3%83%BC%E3%83%A0/members-english?authuser=0){:target="_blank"} (Institute of Science Tokyo)
* [Shinsuke Suzuki](https://sites.google.com/view/szklab/english/top?authuser=0){:target="_blank"} (Hitotsubashi University)

### COSMOS 2023
* Keynote: [Meg Crofoot](https://www.ab.mpg.de/person/99737/2736meg){:target="_blank"} (Max Planck Institute of Animal Behavior)
* [Alberto Acerbi](https://acerbialberto.com/){:target="_blank"} (University of Trento)
* [Anne Kandler](https://www.eva.mpg.de/ecology/staff/anne-kandler/){:target="_blank"} (Max Planck Institute for Evolutionary Anthropology)
* [Judy Fan](https://cogtoolslab.github.io/){:target="_blank"} (Stanford)
* [Julian Jara-Ettinger](https://compdevlab.yale.edu/){:target="_blank"} (Yale)
* [Lei Zhang](https://lei-zhang.net/){:target="_blank"} (University of Birmingham)
* [Robert Hawkins](https://rdhawkins.com/){:target="_blank"} (Stanford)
* [Vivek Hari Sridhar](https://www.vivekhsridhar.com/){:target="_blank"} (University of Washington)


### COSMOS 2022
* Keynote: [Iain Couzin](https://www.ab.mpg.de/person/98158/2736){:target="_blank"} (Max Planck Institute of Animal Behavior)
* [Ariana Strandburg-Peshkin](https://www.ab.mpg.de/cocomo){:target="_blank"} (Max Planck Institute of Animal Behavior)
* [Stefano Palminteri](https://sites.google.com/site/stefanopalminteri/home){:target="_blank"} (ENS Paris)
* [Ralf Kurvers](https://www.mpib-berlin.mpg.de/person/93403){:target="_blank"} (Max Planck Institute for Human Development)
* [Natalia Vélez](https://psychology.princeton.edu/people/natalia-v%C3%A9lez){:target="_blank"} (Princeton)
* [Mark Ho](https://markkho.github.io/){:target="_blank"} (NYU)
* [Elena Miu](https://www.au.dk/en/elena.miu@cas.au.dk){:target="_blank"} (Aarhus University)



