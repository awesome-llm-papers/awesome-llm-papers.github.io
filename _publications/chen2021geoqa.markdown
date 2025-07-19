---
layout: publication
title: 'Geoqa: A Geometric Question Answering Benchmark Towards Multimodal Numerical
  Reasoning'
authors: Chen et al.
conference: 'Findings of the Association for Computational Linguistics: ACL-IJCNLP
  2021'
year: 2021
bibkey: chen2021geoqa
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2105.14517'}]
tags: [Model Architecture, Training Techniques, Evaluation, ACL, Multimodal Models,
  Datasets, Attention Mechanism]
---
Automatic math problem solving has recently attracted increasing attention as
a long-standing AI benchmark. In this paper, we focus on solving geometric
problems, which requires a comprehensive understanding of textual descriptions,
visual diagrams, and theorem knowledge. However, the existing methods were
highly dependent on handcraft rules and were merely evaluated on small-scale
datasets. Therefore, we propose a Geometric Question Answering dataset GeoQA,
containing 4,998 geometric problems with corresponding annotated programs,
which illustrate the solving process of the given problems. Compared with
another publicly available dataset GeoS, GeoQA is 25 times larger, in which the
program annotations can provide a practical testbed for future research on
explicit and explainable numerical reasoning. Moreover, we introduce a Neural
Geometric Solver (NGS) to address geometric problems by comprehensively parsing
multimodal information and generating interpretable programs. We further add
multiple self-supervised auxiliary tasks on NGS to enhance cross-modal semantic
representation. Extensive experiments on GeoQA validate the effectiveness of
our proposed NGS and auxiliary tasks. However, the results are still
significantly lower than human performance, which leaves large room for future
research. Our benchmark and code are released at
https://github.com/chen-judge/GeoQA .