---
layout: publication
title: Explicit Pairwise Word Interaction Modeling Improves Pretrained Transformers
  For English Semantic Similarity Tasks
authors: Zhang Yinan, Tang Raphael, Lin Jimmy
conference: 'Proceedings of the 2016 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2019
bibkey: zhang2019explicit
citations: 111
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.02847'}]
tags: [Model Architecture, BERT, ACL, Transformer, NAACL, Attention Mechanism]
---
In English semantic similarity tasks, classic word embedding-based approaches
explicitly model pairwise "interactions" between the word representations of a
sentence pair. Transformer-based pretrained language models disregard this
notion, instead modeling pairwise word interactions globally and implicitly
through their self-attention mechanism. In this paper, we hypothesize that
introducing an explicit, constrained pairwise word interaction mechanism to
pretrained language models improves their effectiveness on semantic similarity
tasks. We validate our hypothesis using BERT on four tasks in semantic textual
similarity and answer sentence selection. We demonstrate consistent
improvements in quality by adding an explicit pairwise word interaction module
to BERT.