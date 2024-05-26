---
layout: archive
title: "Media"
permalink: /media/
author_profile: true
---

{% include base_path %}
## blah blah.

<img style="float: right;" src="/files/my_pic.jpeg">

Continue markdown text...

*Nov 2023* \
Contributed talk, QEC23, Sydney, Australia

{% for post in site.media reversed %}
  {% include archive-single.html %}
{% endfor %}
