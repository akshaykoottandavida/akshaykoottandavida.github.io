---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---
**Erasure detection of a dual-rail qubit in a 3D superconducting cavity.**\
Contributed talk, QEC23, Sydney, Australia\
*Nov 2023* \
[Link](https://www.youtube.com/watch?v=X74DZZPeUh0)

**Quantum control and error correction with two bosonic modes.**\
Session talk, APS March meeting, Las Vegas, USA\
*Mar 2023*\
[Link](https://www.youtube.com/watch?v=TW4P8gmCnR0)


**Autonomous quantum error correction with pair-cat code.**\
Poster, Gordon Research Conference, Boston, USA\
*Jul 2022* 


**Experimental implementation of pair-cat code with superconducting microwave circuits.**\
Session talk, APS March meeting, Chicago, USA\
*Mar 2022*


**Autonomous quantum error correction with pair-cat code in superconducting microwave circuits.**\
Invited talk, International Conference on Complex Quantum Systems, BARC, Mumbai,India\
*Jun 2021*


**Autonomous quantum error correction with pair-cat code in superconducting microwave circuits.**\
Invited talk, Workshop on Enabling Technology and Algorithms for Quantum Computing,
WACQT, Chalmers, Sweden\
*Apr 2021*


**Experimental implementation of pair-cat code with superconducting microwave circuits.**\
Session talk, APS March meeting, Online\
*Mar 2021*


{% if site.talkmap_link == true %}

<!-- <p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p> -->

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
