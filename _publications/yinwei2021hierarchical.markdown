---
layout: publication
title: Hierarchical User Intent Graph Network Formultimedia Recommendation
authors: Yinwei et al.
conference: IEEE Transactions on Multimedia
year: 2021
bibkey: yinwei2021hierarchical
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.14925'}]
tags: [Tools, Datasets]
---
In this work, we aim to learn multi-level user intents from the co-interacted
patterns of items, so as to obtain high-quality representations of users and
items and further enhance the recommendation performance. Towards this end, we
develop a novel framework, Hierarchical User Intent Graph Network, which
exhibits user intents in a hierarchical graph structure, from the fine-grained
to coarse-grained intents. In particular, we get the multi-level user intents
by recursively performing two operations: 1) intra-level aggregation, which
distills the signal pertinent to user intents from co-interacted item graphs;
and 2) inter-level aggregation, which constitutes the supernode in higher
levels to model coarser-grained user intents via gathering the nodes'
representations in the lower ones. Then, we refine the user and item
representations as a distribution over the discovered intents, instead of
simple pre-existing features. To demonstrate the effectiveness of our model, we
conducted extensive experiments on three public datasets. Our model achieves
significant improvements over the state-of-the-art methods, including MMGCN and
DisenGCN. Furthermore, by visualizing the item representations, we provide the
semantics of user intents.