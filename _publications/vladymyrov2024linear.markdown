---
layout: publication
title: Linear Transformers Are Versatile In-context Learners
authors: Vladymyrov et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2024
bibkey: vladymyrov2024linear
citations: 118
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.14180'}]
tags: [Training Techniques, Attention Mechanism, Transformer, Model Architecture,
  Efficiency And Optimization, Reinforcement Learning, AAAI]
---
Recent research has demonstrated that transformers, particularly linear
attention models, implicitly execute gradient-descent-like algorithms on data
provided in-context during their forward inference step. However, their
capability in handling more complex problems remains unexplored. In this paper,
we prove that each layer of a linear transformer maintains a weight vector for
an implicit linear regression problem and can be interpreted as performing a
variant of preconditioned gradient descent. We also investigate the use of
linear transformers in a challenging scenario where the training data is
corrupted with different levels of noise. Remarkably, we demonstrate that for
this problem linear transformers discover an intricate and highly effective
optimization algorithm, surpassing or matching in performance many reasonable
baselines. We analyze this algorithm and show that it is a novel approach
incorporating momentum and adaptive rescaling based on noise levels. Our
findings show that even linear transformers possess the surprising ability to
discover sophisticated optimization strategies.