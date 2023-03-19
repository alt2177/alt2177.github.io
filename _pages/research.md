---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My current research interests are primarily in variational statistical inference techniques, data analytics, and the mathematical foundations of machine learning. In the past I have also worked on other sectors of research, including Optimal Transport Theory and metric learning, as well as photoacoustics simulations. 

As a sort of overview, my trajectory of research interests went as follows:

Physics (Broadly) --> Data Analysis --> Optimal Transport Theory/Metric Learning --> Machine Learning --> Variational Statistical Inference

It's pretty clear that it took me quite a while to really pinpoint what sort of work I was really interested in doing.

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html %}
{% endfor %}