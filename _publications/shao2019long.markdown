---
layout: publication
title: Long And Diverse Text Generation With Planning-based Hierarchical Variational
  Model
authors: Zhihong Shao, Minlie Huang, Jiangtao Wen, Wenfei Xu, Xiaoyan Zhu
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: shao2019long
citations: 94
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.06605'}]
tags: ["EMNLP"]
short_authors: Shao et al.
---
Existing neural methods for data-to-text generation are still struggling to
produce long and diverse texts: they are insufficient to model input data
dynamically during generation, to capture inter-sentence coherence, or to
generate diversified expressions. To address these issues, we propose a
Planning-based Hierarchical Variational Model (PHVM). Our model first plans a
sequence of groups (each group is a subset of input items to be covered by a
sentence) and then realizes each sentence conditioned on the planning result
and the previously generated context, thereby decomposing long text generation
into dependent sentence generation sub-tasks. To capture expression diversity,
we devise a hierarchical latent structure where a global planning latent
variable models the diversity of reasonable planning and a sequence of local
latent variables controls sentence realization. Experiments show that our model
outperforms state-of-the-art baselines in long and diverse text generation.