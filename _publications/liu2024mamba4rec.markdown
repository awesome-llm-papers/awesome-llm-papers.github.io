---
layout: publication
title: 'Mamba4rec: Towards Efficient Sequential Recommendation With Selective State
  Space Models'
authors: Liu et al.
conference: 'Journal of the Royal Statistical Society Series B: Statistical Methodology'
year: 2024
bibkey: liu2024mamba4rec
citations: 239
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.03900'}]
tags: [Attention Mechanism, Alt, Transformer, Model Architecture, Efficiency And Optimization,
  Datasets]
---
Sequential recommendation aims to estimate the dynamic user preferences and
sequential dependencies among historical user behaviors. Although
Transformer-based models have proven to be effective for sequential
recommendation, they suffer from the inference inefficiency problem stemming
from the quadratic computational complexity of attention operators, especially
for long behavior sequences. Inspired by the recent success of state space
models (SSMs), we propose Mamba4Rec, which is the first work to explore the
potential of selective SSMs for efficient sequential recommendation. Built upon
the basic Mamba block which is a selective SSM with an efficient hardware-aware
parallel algorithm, we design a series of sequential modeling techniques to
further promote model performance while maintaining inference efficiency.
Through experiments on public datasets, we demonstrate how Mamba4Rec
effectively tackles the effectiveness-efficiency dilemma, outperforming both
RNN- and attention-based baselines in terms of both effectiveness and
efficiency. The code is available at https://github.com/chengkai-liu/Mamba4Rec.