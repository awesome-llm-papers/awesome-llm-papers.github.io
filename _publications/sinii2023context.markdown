---
layout: publication
title: In-context Reinforcement Learning For Variable Action Spaces
authors: Sinii et al.
conference: 2007 IEEE International Symposium on Approximate Dynamic Programming and
  Reinforcement Learning
year: 2023
bibkey: sinii2023context
citations: 112
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.13327'}]
tags: [Training Techniques, Agentic, Transformer, Model Architecture, Reinforcement
    Learning, Applications, Datasets]
---
Recently, it has been shown that transformers pre-trained on diverse datasets
with multi-episode contexts can generalize to new reinforcement learning tasks
in-context. A key limitation of previously proposed models is their reliance on
a predefined action space size and structure. The introduction of a new action
space often requires data re-collection and model re-training, which can be
costly for some applications. In our work, we show that it is possible to
mitigate this issue by proposing the Headless-AD model that, despite being
trained only once, is capable of generalizing to discrete action spaces of
variable size, semantic content and order. By experimenting with Bernoulli and
contextual bandits, as well as a gridworld environment, we show that
Headless-AD exhibits significant capability to generalize to action spaces it
has never encountered, even outperforming specialized models trained for a
specific set of actions on several environment configurations. Implementation
is available at: https://github.com/corl-team/headless-ad.