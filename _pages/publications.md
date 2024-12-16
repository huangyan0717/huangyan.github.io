---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?hl=zh-CN&user=5P3TXU0AAAAJ&view_op=list_works&sortby=pubdate}}">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications %}
  {% include archive-single.html %}
{% endfor %}
