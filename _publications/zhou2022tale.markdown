---
layout: publication
title: 'A Tale Of Two Graphs: Freezing And Denoising Graph Structures For Multimodal
  Recommendation'
authors: Zhou Xin, Shen Zhiqi
conference: Proceedings of the 31st ACM International Conference on Multimedia
year: 2022
bibkey: zhou2022tale
citations: 64
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.06924'}]
tags: [RAG, Training Techniques, Efficiency And Optimization, Reinforcement Learning,
  Multimodal Models, Pruning, Datasets]
---
Multimodal recommender systems utilizing multimodal features (e.g., images
and textual descriptions) typically show better recommendation accuracy than
general recommendation models based solely on user-item interactions.
Generally, prior work fuses multimodal features into item ID embeddings to
enrich item representations, thus failing to capture the latent semantic
item-item structures. In this context, LATTICE proposes to learn the latent
structure between items explicitly and achieves state-of-the-art performance
for multimodal recommendations. However, we argue the latent graph structure
learning of LATTICE is both inefficient and unnecessary. Experimentally, we
demonstrate that freezing its item-item structure before training can also
achieve competitive performance. Based on this finding, we propose a simple yet
effective model, dubbed as FREEDOM, that FREEzes the item-item graph and
DenOises the user-item interaction graph simultaneously for Multimodal
recommendation. Theoretically, we examine the design of FREEDOM through a graph
spectral perspective and demonstrate that it possesses a tighter upper bound on
the graph spectrum. In denoising the user-item interaction graph, we devise a
degree-sensitive edge pruning method, which rejects possibly noisy edges with a
high probability when sampling the graph. We evaluate the proposed model on
three real-world datasets and show that FREEDOM can significantly outperform
current strongest baselines. Compared with LATTICE, FREEDOM achieves an average
improvement of 19.07% in recommendation accuracy while reducing its memory cost
up to 6\\(\times\\) on large graphs. The source code is available at:
https://github.com/enoche/FREEDOM.