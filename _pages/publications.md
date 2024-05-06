---
layout: talk
title: "Publications"
permalink: /publications/
author_profile: true
---
You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=0RVMZkUAAAAJ&hl=en}}">my Google Scholar profile</a>.</u>

{% include base_path %}

_Full publication list on [Google Scholar](https://scholar.google.com/citations?user=0RVMZkUAAAAJ&hl=en)_


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<sup>*</sup> Authors contributed equally to this work
