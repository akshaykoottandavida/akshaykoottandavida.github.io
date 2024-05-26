---
layout: archive
title: "Media"
permalink: /media/
author_profile: true
---

{% include base_path %}
## blah blah.

<!-- | ![Flowers](/images/my_pic.jpeg) | I am text to the right | -->

<div style="float:left;margin:0 10px 10px 0" markdown="1">
    ![book](/images/my_pic.jpeg)
</div>

{% for post in site.media reversed %}
  {% include archive-single.html %}
{% endfor %}
