---
layout: publication
title: 'Compositional Generalization And Natural Language Variation: Can A Semantic
  Parsing Approach Handle Both?'
authors: Peter Shaw, Ming-wei Chang, Panupong Pasupat, Kristina Toutanova
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: shaw2020compositional
citations: 104
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.12725'}]
tags: ["Datasets"]
short_authors: Shaw et al.
---
Sequence-to-sequence models excel at handling natural language variation, but
have been shown to struggle with out-of-distribution compositional
generalization. This has motivated new specialized architectures with stronger
compositional biases, but most of these approaches have only been evaluated on
synthetically-generated datasets, which are not representative of natural
language variation. In this work we ask: can we develop a semantic parsing
approach that handles both natural language variation and compositional
generalization? To better assess this capability, we propose new train and test
splits of non-synthetic datasets. We demonstrate that strong existing
approaches do not perform well across a broad set of evaluations. We also
propose NQG-T5, a hybrid model that combines a high-precision grammar-based
approach with a pre-trained sequence-to-sequence model. It outperforms existing
approaches across several compositional generalization challenges on
non-synthetic data, while also being competitive with the state-of-the-art on
standard evaluations. While still far from solving this problem, our study
highlights the importance of diverse evaluations and the open challenge of
handling both compositional generalization and natural language variation in
semantic parsing.