---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---
### Erasure detection of a dual-rail qubit in a 3D superconducting cavity.
*Nov 20234* \
Contributed talk, QEC23, Sydney, Australia

### Quantum control and error correction with two bosonic modes.
*Mar 2023*\
Session talk, APS March meeting, Las Vegas, USA

### Autonomous quantum error correction with pair-cat code.
*Jul 2022* \
Poster, Gordon Research Conference, Boston, USA

### Experimental implementation of pair-cat code with superconducting microwave circuits.
*Mar 2022*\
Session talk, APS March meeting, Chicago, USA

### Autonomous quantum error correction with pair-cat code in superconducting microwave circuits.
*Jun 2021*\
Invited talk, International Conference on Complex Quantum Systems, BARC, Mumbai,India

### Autonomous quantum error correction with pair-cat code in superconducting microwave circuits.
*Apr 2021*\
Invited talk, Workshop on Enabling Technology and Algorithms for Quantum Computing,
WACQT, Chalmers, Sweden

### Experimental implementation of pair-cat code with superconducting microwave circuits.
*Mar 2021*\
Session talk, APS March meeting, Online

{% if site.talkmap_link == true %}

<!-- <p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p> -->

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
