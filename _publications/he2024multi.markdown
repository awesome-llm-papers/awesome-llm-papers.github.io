---
layout: publication
title: Multi-grained Preference Enhanced Transformer For Multi-behavior Sequential
  Recommendation
authors: He et al.
conference: Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and
  Data Mining
year: 2024
bibkey: he2024multi
citations: 112
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.12179'}]
tags: [GPT, Tools, Transformer, Model Architecture, Reinforcement Learning, Datasets,
  KDD]
---
Sequential recommendation (SR) aims to predict the next purchasing item
according to users' dynamic preference learned from their historical user-item
interactions. To improve the performance of recommendation, learning dynamic
heterogeneous cross-type behavior dependencies is indispensable for recommender
system. However, there still exists some challenges in Multi-Behavior
Sequential Recommendation (MBSR). On the one hand, existing methods only model
heterogeneous multi-behavior dependencies at behavior-level or item-level, and
modelling interaction-level dependencies is still a challenge. On the other
hand, the dynamic multi-grained behavior-aware preference is hard to capture in
interaction sequences, which reflects interaction-aware sequential pattern. To
tackle these challenges, we propose a Multi-Grained Preference enhanced
Transformer framework (M-GPT). First, M-GPT constructs a interaction-level
graph of historical cross-typed interactions in a sequence. Then graph
convolution is performed to derive interaction-level multi-behavior dependency
representation repeatedly, in which the complex correlation between historical
cross-typed interactions at specific orders can be well learned. Secondly, a
novel multi-scale transformer architecture equipped with multi-grained user
preference extraction is proposed to encode the interaction-aware sequential
pattern enhanced by capturing temporal behavior-aware multi-grained preference
. Experiments on the real-world datasets indicate that our method M-GPT
consistently outperforms various state-of-the-art recommendation methods.