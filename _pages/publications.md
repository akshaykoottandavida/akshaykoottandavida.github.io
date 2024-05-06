---
layout: talk
title: "Publications"
permalink: /publications/
author_profile: true
---
You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<sup>*</sup> Authors contributed equally to this work
