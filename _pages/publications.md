---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

<ul>
  <!-- 筛选并逆序排列个人论文 -->
  {% assign my_papers = site.publications | where_exp: "post", "post.label starts_with 'm_'" | sort: "label" | reverse %}

  <!-- 筛选并逆序排列合作论文 -->
  {% assign co_papers = site.publications | where_exp: "post", "post.label starts_with 'c_'" | sort: "label" | reverse %}

  <!-- 列出个人论文 -->
  <h3>My Papers</h3>
  {% for post in my_papers %}
    {% include base_path %}
  {% endfor %}

  <!-- 列出合作论文 -->
  <h3>Collaborative Papers</h3>
  {% for post in co_papers %}
    {% include base_path %}
  {% endfor %}
</ul>
