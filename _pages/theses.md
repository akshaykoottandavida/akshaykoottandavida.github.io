---
layout: archive
title: "Theses"
permalink: /theses/
author_profile: true
---

{% include base_path %}
## PhD. Thesis
Title : Multimode bosonic quantum error correction\
Advisor : Prof. Michel Devoret, Yale University, USA

## Masters Thesis
Title : [Nonreciprocal devices in microwave circuit optomechanics](/files/masters_thesis.pdf)\
Advisor : Prof. Tobias Kippenberg, École Polytechnique Fédérale de Lausanne, Switzerland

{% for post in site.theses reversed %}
  {% include archive-single.html %}
{% endfor %}
