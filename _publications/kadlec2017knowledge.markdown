---
layout: publication
title: 'Knowledge Base Completion: Baselines Strike Back'
authors: Kadlec Rudolf, Bajgar Ondrej, Kleindienst Jan
conference: Proceedings of the 2nd Workshop on Representation Learning for NLP
year: 2017
bibkey: kadlec2017knowledge
citations: 164
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1705.10744'}]
tags: [Training Techniques, Prompting, Model Architecture, Reinforcement Learning,
  Datasets]
---
Many papers have been published on the knowledge base completion task in the
past few years. Most of these introduce novel architectures for relation
learning that are evaluated on standard datasets such as FB15k and WN18. This
paper shows that the accuracy of almost all models published on the FB15k can
be outperformed by an appropriately tuned baseline - our reimplementation of
the DistMult model. Our findings cast doubt on the claim that the performance
improvements of recent models are due to architectural changes as opposed to
hyper-parameter tuning or different training objectives. This should prompt
future research to re-consider how the performance of models is evaluated and
reported.