---
layout: publication
title: Competence-based Multimodal Curriculum Learning For Medical Report Generation
authors: Fenglin Liu, Shen Ge, Yuexian Zou, Xian Wu
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: liu2021competence
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2206.14579'}]
tags: ["Training Techniques"]
short_authors: Liu et al.
---
Medical report generation task, which targets to produce long and coherent
descriptions of medical images, has attracted growing research interests
recently. Different from the general image captioning tasks, medical report
generation is more challenging for data-driven neural models. This is mainly
due to 1) the serious data bias and 2) the limited medical data. To alleviate
the data bias and make best use of available data, we propose a
Competence-based Multimodal Curriculum Learning framework (CMCL). Specifically,
CMCL simulates the learning process of radiologists and optimizes the model in
a step by step manner. Firstly, CMCL estimates the difficulty of each training
instance and evaluates the competence of current model; Secondly, CMCL selects
the most suitable batch of training instances considering current model
competence. By iterating above two steps, CMCL can gradually improve the
model's performance. The experiments on the public IU-Xray and MIMIC-CXR
datasets show that CMCL can be incorporated into existing models to improve
their performance.