---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Preprints
======

**Meta-Learning Adaptable Foundation Models**<br>
<span style="line-height: 1;">Jacob L. Block, ***SS**, Liam Collins, Aryan Mokhtari, Sanjay Shakkottai*</span><br>
<span style="line-height: 1;">arXiv preprint</span><br>
<span style="line-height: 1;">[[PDF]](https://arxiv.org/abs/2410.22264)</span>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
