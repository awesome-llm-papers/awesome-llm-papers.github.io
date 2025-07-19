---
layout: publication
title: Multi-head Or Single-head? An Empirical Comparison For Transformer Training
authors: Liu Liyuan, Liu Jialu, Han Jiawei
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
bibkey: liu2021multi
citations: 121
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.09650'}]
tags: [Training Techniques, Attention Mechanism, EMNLP, BERT, Transformer, Model Architecture,
  Applications]
---
Multi-head attention plays a crucial role in the recent success of
Transformer models, which leads to consistent performance improvements over
conventional attention in various applications. The popular belief is that this
effectiveness stems from the ability of jointly attending multiple positions.
In this paper, we first demonstrate that jointly attending multiple positions
is not a unique feature of multi-head attention, as multi-layer single-head
attention also attends multiple positions and is more effective. Then, we
suggest the main advantage of the multi-head attention is the training
stability, since it has less number of layers than the single-head attention,
when attending the same number of positions. For example, 24-layer 16-head
Transformer (BERT-large) and 384-layer single-head Transformer has the same
total attention head number and roughly the same model size, while the
multi-head one is significantly shallower. Meanwhile, we show that, with recent
advances in deep learning, we can successfully stabilize the training of the
384-layer Transformer. As the training difficulty is no longer a bottleneck,
substantially deeper single-head Transformer achieves consistent performance
improvements without tuning hyper-parameters.