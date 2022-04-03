---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

A short introduction of my project in layman's term can be found [here](https://gulp.curtin.edu.au/local/docs/gulp/gulp_31_manual/gulpnode23.html).

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
