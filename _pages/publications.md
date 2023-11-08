---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

2023
======

Chen Yong, Gui Xinfeng, **Zeng Jinshan**, Zhao Xi-Le, He Wei. Combining Low-Rank and Deep Plug-and-Play Priors for Snapshot Compressive Imaging. IEEE Transactions on Neural Networks and Learning Systems.

**Jinshan Zeng**, Ruiying Xu, Yu Wu, Hongwei Li, Jiaxing Lu. Zero-Shot Chinese Character Recognition with Stroke-and Radical-Level Decompositions. International Joint Conference on Neural Networks (IJCNN).

**Jinshan Zeng**, Ling Tu, Jie Zhou, Yefei Wang, Jiguo Zeng. Enhancing Chinese Calligraphy Generation with Contour and Region-aware Attention. International Joint Conference on Neural Networks (IJCNN).


2022
======

**Jinshan Zeng**, Yudong Xie, Xianglong Yu, John SY Lee, Ding-Xuan Zhou. Enhancing automatic readability assessment with pre-training and soft labels for ordinal regression. Findings of the Association for Computational Linguistics: EMNLP 2022.
