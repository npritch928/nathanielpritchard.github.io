---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Nathaniel Pritchard a PhD canidate in Statistics at the University of Wisconsin - Madison.  I am interested in Randomized Linear Algebra especially with respect to statstical techniques such as linear regresssion and Generalized Linear Models.

Recent Papers
======

<ol>{% for post in site.publications reversed %}
  {% if forloop.index < 6  %}
   <li> {%include archive-single-publication-about.html %}</li>
  {% endif %}
{% endfor %}</ol>

