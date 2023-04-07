---
layout: archive
title: "Slides"
permalink: /slides/
author_profile: true
---
Here's some more information about slides 
[lecture 1](https://github.com/smcnew/ECOL_596_DataScience/blob/master/files/Lecture1.pdf)

{% include base_path %}

{% for post in site.slides reversed %}
  {% include archive-single.html %}
{% endfor %}
