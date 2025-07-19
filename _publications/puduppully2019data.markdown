---
layout: publication
title: Data-to-text Generation With Entity Modeling
authors: Puduppully Ratish, Dong Li, Lapata Mirella
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: puduppully2019data
citations: 121
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.03221'}]
tags: [Model Architecture, Evaluation, ACL, Datasets, Language Modeling, Attention
    Mechanism]
---
Recent approaches to data-to-text generation have shown great promise thanks
to the use of large-scale datasets and the application of neural network
architectures which are trained end-to-end. These models rely on representation
learning to select content appropriately, structure it coherently, and
verbalize it grammatically, treating entities as nothing more than vocabulary
tokens. In this work we propose an entity-centric neural architecture for
data-to-text generation. Our model creates entity-specific representations
which are dynamically updated. Text is generated conditioned on the data input
and entity memory representations using hierarchical attention at each time
step. We present experiments on the RotoWire benchmark and a (five times
larger) new dataset on the baseball domain which we create. Our results show
that the proposed model outperforms competitive baselines in automatic and
human evaluation.