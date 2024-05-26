---
layout: archive
title: "Media"
permalink: /media/
author_profile: true
---

{% include base_path %}
## blah blah.

<!-- | ![Flowers](/images/my_pic.jpeg) | I am text to the right | -->

<div style="clear: both;">
  <div style="float: left; margin-right 1em;">
    <img src="/images/my_pic.jpeg" alt="">
  </div>
  <div>
    <h2>Some title text</h2>
    <p>Some more text that will appear to the left of the image.</p>
  </div>
</div>

{% for post in site.media reversed %}
  {% include archive-single.html %}
{% endfor %}
