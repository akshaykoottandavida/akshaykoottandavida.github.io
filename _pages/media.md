---
layout: archive
title: "Media"
permalink: /media/
author_profile: true
---

{% include base_path %}
## blah blah.

<!-- | ![Flowers](/images/my_pic.jpeg) | I am text to the right | -->

<h1><img src="/images/my_pic.jpeg">American Title</h1>

{% for post in site.media reversed %}
  {% include archive-single.html %}
{% endfor %}
