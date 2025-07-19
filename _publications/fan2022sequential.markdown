---
layout: publication
title: Sequential Recommendation Via Stochastic Self-attention
authors: Fan et al.
conference: Proceedings of the ACM Web Conference 2022
year: 2022
bibkey: fan2022sequential
citations: 119
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2201.06035'}]
tags: [Training Techniques, Attention Mechanism, Evaluation, Transformer, Model Architecture,
  Efficiency And Optimization, Reinforcement Learning, Datasets]
---
Sequential recommendation models the dynamics of a user's previous behaviors
in order to forecast the next item, and has drawn a lot of attention.
Transformer-based approaches, which embed items as vectors and use dot-product
self-attention to measure the relationship between items, demonstrate superior
capabilities among existing sequential methods. However, users' real-world
sequential behaviors are \textit\{\textbf\{uncertain\}\} rather than deterministic,
posing a significant challenge to present techniques. We further suggest that
dot-product-based approaches cannot fully capture \textit\{\textbf\{collaborative
transitivity\}\}, which can be derived in item-item transitions inside sequences
and is beneficial for cold start items. We further argue that BPR loss has no
constraint on positive and sampled negative items, which misleads the
optimization. We propose a novel \textbf\{STO\}chastic
\textbf\{S\}elf-\textbf\{A\}ttention~(STOSA) to overcome these issues. STOSA, in
particular, embeds each item as a stochastic Gaussian distribution, the
covariance of which encodes the uncertainty. We devise a novel Wasserstein
Self-Attention module to characterize item-item position-wise relationships in
sequences, which effectively incorporates uncertainty into model training.
Wasserstein attentions also enlighten the collaborative transitivity learning
as it satisfies triangle inequality. Moreover, we introduce a novel
regularization term to the ranking loss, which assures the dissimilarity
between positive and the negative items. Extensive experiments on five
real-world benchmark datasets demonstrate the superiority of the proposed model
over state-of-the-art baselines, especially on cold start items. The code is
available in https://github.com/zfan20/STOSA.