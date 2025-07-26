---
layout: publication
title: Improving Adversarial Text Generation By Modeling The Distant Future
authors: Ruiyi Zhang, Changyou Chen, Zhe Gan, Wenlin Wang, Dinghan Shen, Guoyin Wang,
  Zheng Wen, Lawrence Carin
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: zhang2020improving
citations: 201
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.01279'}]
tags: ["Efficiency", "Security"]
short_authors: Zhang et al.
---
Auto-regressive text generation models usually focus on local fluency, and
may cause inconsistent semantic meaning in long text generation. Further,
automatically generating words with similar semantics is challenging, and
hand-crafted linguistic rules are difficult to apply. We consider a text
planning scheme and present a model-based imitation-learning approach to
alleviate the aforementioned issues. Specifically, we propose a novel guider
network to focus on the generative process over a longer horizon, which can
assist next-word prediction and provide intermediate rewards for generator
optimization. Extensive experiments demonstrate that the proposed method leads
to improved performance.