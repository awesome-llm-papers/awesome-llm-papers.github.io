---
layout: publication
title: Knowledge-enhanced Hierarchical Graph Transformer Network For Multi-behavior
  Recommendation
authors: Xia et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2021
bibkey: xia2021knowledge
citations: 178
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.04000'}]
tags: [Attention Mechanism, Tools, Evaluation, Transformer, Model Architecture, Time
    Series, Reinforcement Learning, AAAI, Datasets]
---
Accurate user and item embedding learning is crucial for modern recommender
systems. However, most existing recommendation techniques have thus far focused
on modeling users' preferences over singular type of user-item interactions.
Many practical recommendation scenarios involve multi-typed user interactive
behaviors (e.g., page view, add-to-favorite and purchase), which presents
unique challenges that cannot be handled by current recommendation solutions.
In particular: i) complex inter-dependencies across different types of user
behaviors; ii) the incorporation of knowledge-aware item relations into the
multi-behavior recommendation framework; iii) dynamic characteristics of
multi-typed user-item interactions. To tackle these challenges, this work
proposes a Knowledge-Enhanced Hierarchical Graph Transformer Network (KHGT), to
investigate multi-typed interactive patterns between users and items in
recommender systems. Specifically, KHGT is built upon a graph-structured neural
architecture to i) capture type-specific behavior characteristics; ii)
explicitly discriminate which types of user-item interactions are more
important in assisting the forecasting task on the target behavior.
Additionally, we further integrate the graph attention layer with the temporal
encoding strategy, to empower the learned embeddings be reflective of both
dedicated multiplex user-item and item-item relations, as well as the
underlying interaction dynamics. Extensive experiments conducted on three
real-world datasets show that KHGT consistently outperforms many
state-of-the-art recommendation methods across various evaluation settings. Our
implementation code is available at https://github.com/akaxlh/KHGT.