---
layout: publication
title: Fast Context Adaptation Via Meta-learning
authors: Luisa M Zintgraf, Kyriacos Shiarlis, Vitaly Kurin, Katja Hofmann, Shimon
  Whiteson
conference: Arxiv
year: 2018
bibkey: zintgraf2018fast
citations: 184
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1810.03642'}]
tags: ["Reinforcement Learning"]
short_authors: Zintgraf et al.
---
We propose CAVIA for meta-learning, a simple extension to MAML that is less
prone to meta-overfitting, easier to parallelise, and more interpretable. CAVIA
partitions the model parameters into two parts: context parameters that serve
as additional input to the model and are adapted on individual tasks, and
shared parameters that are meta-trained and shared across tasks. At test time,
only the context parameters are updated, leading to a low-dimensional task
representation. We show empirically that CAVIA outperforms MAML for regression,
classification, and reinforcement learning. Our experiments also highlight
weaknesses in current benchmarks, in that the amount of adaptation needed in
some cases is small.