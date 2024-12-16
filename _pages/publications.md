---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

  My articles are also on [my Google Scholar profile](https://scholar.google.com/citations?user=5P3TXU0AAAAJ&hl=en).


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
