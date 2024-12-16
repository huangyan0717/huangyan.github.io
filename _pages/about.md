---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome! I am currently a postdoc in the Division of Decision and Control Systems at KTH, Sweden, under the supervision of Prof. Karl Henrik Johansson. Before that, I got my Ph.D. at the College of Control Science and Engineering, Zhejiang University, supervised by Prof. Jinming Xu and Prof. Jiming Chen. My research interests include distributed/federated optimization, large-scale machine learning, and differentially private computing.

Education
======
* Ph.D in Control Science and Control Engineering, Zhejiang University, 2020-2024
* M.S. in Control Science and Control Engineering, Southeast University, 2017-2020
* B.S. in Automation, Anhui University, 2013-2017

Visiting
======
* 2023.02 - 2023.08:  Visiting PhD student, ETH Zurich
  * Department of Computer Science, ETH Zurich, Switzerland
  * Working on distributed adaptive minimax optimization in the Optimization and Decision Intelligence (ODI) group
  * Host: Prof. Niao He

Accomplishments
======
* “Outstanding Graduate”, Zhejiang University, 2024
* “Outstanding Doctoral Student”, Zhejiang University, 2022 and 2023
* 2nd prize of 14th China Post-graduate Mathematical Contest in Modeling, 2017
* “Outstanding Graduate”, Anhui University, 2017

Publications
======
  <ul>
  <!-- 筛选出个人论文（文件名以 m_ 开头），按文件名逆序排列 -->
  {% assign my_papers = site.publications | sort: "url" | reverse %}
  {% assign my_papers = my_papers | where_exp: "post", "post.url contains '/m_'" %}

  <!-- 筛选出合作论文（文件名以 c_ 开头），按文件名逆序排列 -->
  {% assign co_papers = site.publications | sort: "url" | reverse %}
  {% assign co_papers = co_papers | where_exp: "post", "post.url contains '/c_'" %}

  <!-- 列出个人论文 -->
  {% for post in my_papers %}
    {% include archive-single-cv.html %}
  {% endfor %}

  <!-- 列出合作论文 -->
  {% for post in co_papers %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>


