---
layout: publication
title: Denoising Self-attentive Sequential Recommendation
authors: Chen et al.
conference: Proceedings of the 16th ACM Conference on Recommender Systems
year: 2022
bibkey: chen2022denoising
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.04120'}]
tags: [Model Architecture, Transformer, RecSys, Reinforcement Learning, Attention
    Mechanism]
---
Transformer-based sequential recommenders are very powerful for capturing
both short-term and long-term sequential item dependencies. This is mainly
attributed to their unique self-attention networks to exploit pairwise
item-item interactions within the sequence. However, real-world item sequences
are often noisy, which is particularly true for implicit feedback. For example,
a large portion of clicks do not align well with user preferences, and many
products end up with negative reviews or being returned. As such, the current
user action only depends on a subset of items, not on the entire sequences.
Many existing Transformer-based models use full attention distributions, which
inevitably assign certain credits to irrelevant items. This may lead to
sub-optimal performance if Transformers are not regularized properly.