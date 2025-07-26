---
layout: publication
title: 'UNIMO: Towards Unified-modal Understanding And Generation Via Cross-modal
  Contrastive Learning'
authors: Wei Li, Can Gao, Guocheng Niu, Xinyan Xiao, Hao Liu, Jiachen Liu, Hua Wu,
  Haifeng Wang
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: li2020unimo
citations: 210
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.15409'}]
tags: ["Has Code", "Model Architecture"]
short_authors: Li et al.
---
Existed pre-training methods either focus on single-modal tasks or
multi-modal tasks, and cannot effectively adapt to each other. They can only
utilize single-modal data (i.e. text or image) or limited multi-modal data
(i.e. image-text pairs). In this work, we propose a unified-modal pre-training
architecture, namely UNIMO, which can effectively adapt to both single-modal
and multi-modal understanding and generation tasks. Large scale of free text
corpus and image collections can be utilized to improve the capability of
visual and textual understanding, and cross-modal contrastive learning (CMCL)
is leveraged to align the textual and visual information into a unified
semantic space over a corpus of image-text pairs. As the non-paired
single-modal data is very rich, our model can utilize much larger scale of data
to learn more generalizable representations. Moreover, the textual knowledge
and visual knowledge can enhance each other in the unified semantic space. The
experimental results show that UNIMO significantly improves the performance of
several single-modal and multi-modal downstream tasks. Our code and pre-trained
models are public at the UNIMO project page https://unimo-ptm.github.io/