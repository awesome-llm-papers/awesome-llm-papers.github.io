---
layout: publication
title: 'Length-adaptive Transformer: Train Once With Length Drop, Use Anytime With
  Search'
authors: Gyuwan Kim, Kyunghyun Cho
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2020
citations: 22
bibkey: kim2020length
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.07003'}, {name: Code,
    url: 'https://github.com/clovaai/length-adaptive-transformer'}]
tags: [Has Code, Model Architecture, Transformer, BERT, Efficiency and Optimization,
  Training Techniques]
---
Despite transformers' impressive accuracy, their computational cost is often
prohibitive to use with limited computational resources. Most previous
approaches to improve inference efficiency require a separate model for each
possible computational budget. In this paper, we extend PoWER-BERT (Goyal et
al., 2020) and propose Length-Adaptive Transformer that can be used for various
inference scenarios after one-shot training. We train a transformer with
LengthDrop, a structural variant of dropout, which stochastically determines a
sequence length at each layer. We then conduct a multi-objective evolutionary
search to find a length configuration that maximizes the accuracy and minimizes
the efficiency metric under any given computational budget. Additionally, we
significantly extend the applicability of PoWER-BERT beyond sequence-level
classification into token-level classification with Drop-and-Restore process
that drops word-vectors temporarily in intermediate layers and restores at the
last layer if necessary. We empirically verify the utility of the proposed
approach by demonstrating the superior accuracy-efficiency trade-off under
various setups, including span-based question answering and text
classification. Code is available at
https://github.com/clovaai/length-adaptive-transformer.