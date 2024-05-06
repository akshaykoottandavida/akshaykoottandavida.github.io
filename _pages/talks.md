---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---
### Erasure detection of a dual-rail qubit in a 3D superconducting cavity.
*Nov 2023* \
Contributed talk, QEC23, Sydney, Australia

{% if site.talkmap_link == true %}

<!-- <p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p> -->

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
