---
layout: archive
title: "Code"
permalink: /code/
author_profile: true
---
Here's a list of exercises and code from class 

{% include base_path %}

{% for post in site.code reversed %}
  {% include archive-single.html %}
{% endfor %}
