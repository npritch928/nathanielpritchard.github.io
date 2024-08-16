---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Nathaniel Pritchard, a Post Doc at the University of Oxford.  I am interested in Randomized Linear Algebra especially with respect to statistical techniques such as linear regression and Generalized Linear Models.

Recent Papers
======

<ol>{% for post in site.publications reversed %}
  {% if forloop.index < 6  %}
   <li> {%include archive-single-publication-about.html %}</li>
  {% endif %}
{% endfor %}</ol>

