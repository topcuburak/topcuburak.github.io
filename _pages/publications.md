---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

ABCA
ABCD

title: "2022 - Performance Evaluation of CUDA Optimizations for Convolution Operations"
Performance_Evaluation_of_CUDA_Optimizations_for_Convolution_Operations
date: 2022-05-12
venue: 'BASARIM 2022 - 7th High-Performance Computing Conference'
citation: 'B. Topçu and I. Öz, "Performance Evaluation of CUDA Optimizations for Convolution Operations," BAŞARIM 2022 - 7th High-Performance Computing Conference, Istanbul, Turkiye, 2022'


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
