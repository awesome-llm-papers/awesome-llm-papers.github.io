---
layout: publication
title: Efficiently Leveraging Multi-level User Intent For Session-based Recommendation
  Via Atten-mixer Network
authors: Zhang et al.
conference: Proceedings of the Sixteenth ACM International Conference on Web Search
  and Data Mining
year: 2022
bibkey: zhang2022efficiently
citations: 77
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2206.12781'}]
tags: [RAG, Attention Mechanism, Evaluation, Ethics And Bias, Model Architecture,
  Efficiency And Optimization, Reinforcement Learning, Datasets]
---
Session-based recommendation (SBR) aims to predict the user's next action
based on short and dynamic sessions. Recently, there has been an increasing
interest in utilizing various elaborately designed graph neural networks (GNNs)
to capture the pair-wise relationships among items, seemingly suggesting the
design of more complicated models is the panacea for improving the empirical
performance. However, these models achieve relatively marginal improvements
with exponential growth in model complexity. In this paper, we dissect the
classical GNN-based SBR models and empirically find that some sophisticated GNN
propagations are redundant, given the readout module plays a significant role
in GNN-based models. Based on this observation, we intuitively propose to
remove the GNN propagation part, while the readout module will take on more
responsibility in the model reasoning process. To this end, we propose the
Multi-Level Attention Mixture Network (Atten-Mixer), which leverages both
concept-view and instance-view readouts to achieve multi-level reasoning over
item transitions. As simply enumerating all possible high-level concepts is
infeasible for large real-world recommender systems, we further incorporate
SBR-related inductive biases, i.e., local invariance and inherent priority to
prune the search space. Experiments on three benchmarks demonstrate the
effectiveness and efficiency of our proposal. We also have already launched the
proposed techniques to a large-scale e-commercial online service since April
2021, with significant improvements of top-tier business metrics demonstrated
in the online experiments on live traffic.