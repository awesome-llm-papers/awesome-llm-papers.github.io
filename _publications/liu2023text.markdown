---
layout: publication
title: Text Matching Improves Sequential Recommendation By Reducing Popularity Biases
authors: Zhenghao Liu et al.
conference: 'CIKM ''23: The 32nd ACM International Conference on Information and Knowledge
  Management'
year: 2023
citations: 18
bibkey: liu2023text
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.14029'}, {name: Code,
    url: 'https://github.com/OpenMatch/TASTE'}]
tags: [Has Code, Model Architecture, Attention Mechanism, Ethics and Bias, Transformer]
---
This paper proposes Text mAtching based SequenTial rEcommendation model
(TASTE), which maps items and users in an embedding space and recommends items
by matching their text representations. TASTE verbalizes items and user-item
interactions using identifiers and attributes of items. To better characterize
user behaviors, TASTE additionally proposes an attention sparsity method, which
enables TASTE to model longer user-item interactions by reducing the
self-attention computations during encoding. Our experiments show that TASTE
outperforms the state-of-the-art methods on widely used sequential
recommendation datasets. TASTE alleviates the cold start problem by
representing long-tail items using full-text modeling and bringing the benefits
of pretrained language models to recommendation systems. Our further analyses
illustrate that TASTE significantly improves the recommendation accuracy by
reducing the popularity bias of previous item id based recommendation models
and returning more appropriate and text-relevant items to satisfy users. All
codes are available at https://github.com/OpenMatch/TASTE.