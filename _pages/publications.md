---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

<h2> Full list of publication on <u><a href="https://scholar.google.com/citations?user=FNN4IasAAAAJ&hl=en&authuser=1">Google Scholar profile</a>.</u> </h2>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
