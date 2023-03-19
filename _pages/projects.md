---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

Here you will find a variety of projects I've worked on in the past. They cover a wide variety of work, everything from machine learning to software engineering to business analytics. 


{% include base_path %}

{% assign ordered_pages = site.projects | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html %}
{% endfor %}