---
layout: archive
title: "Media"
permalink: /media/
author_profile: true
---

{% include base_path %}
<img src="/images/erasure.png" alt="drawing" width="200"/>
[**Quantum errors raise a flag, Yale Quantum Institute, 2024**](https://quantuminstitute.yale.edu/news/quantum-errors-raise-flag)


<img src="/images/nonrecip.jpg" alt="drawing" width="200"/>
[**One-way track for microwaves based on mechanical interference**](https://actu.epfl.ch/news/one-way-track-for-microwaves-based-on-mechanical-i/)

<!-- | ![Flowers](/images/my_pic.jpeg) | I am text to the right | -->

{% for post in site.media reversed %}
  {% include archive-single.html %}
{% endfor %}
