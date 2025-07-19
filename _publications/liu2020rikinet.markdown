---
layout: publication
title: 'Rikinet: Reading Wikipedia Pages For Natural Question Answering'
authors: Liu et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: liu2020rikinet
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.14560'}]
tags: [Model Architecture, Evaluation, ACL, Transformer, RAG, Datasets, Attention
    Mechanism]
---
Reading long documents to answer open-domain questions remains challenging in
natural language understanding. In this paper, we introduce a new model, called
RikiNet, which reads Wikipedia pages for natural question answering. RikiNet
contains a dynamic paragraph dual-attention reader and a multi-level cascaded
answer predictor. The reader dynamically represents the document and question
by utilizing a set of complementary attention mechanisms. The representations
are then fed into the predictor to obtain the span of the short answer, the
paragraph of the long answer, and the answer type in a cascaded manner. On the
Natural Questions (NQ) dataset, a single RikiNet achieves 74.3 F1 and 57.9 F1
on long-answer and short-answer tasks. To our best knowledge, it is the first
single model that outperforms the single human performance. Furthermore, an
ensemble RikiNet obtains 76.1 F1 and 61.3 F1 on long-answer and short-answer
tasks, achieving the best performance on the official NQ leaderboard