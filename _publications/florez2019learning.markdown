---
layout: publication
title: Learning To Control Latent Representations For Few-shot Learning Of Named Entities
authors: Florez Omar U., Mueller Erik
conference: IEEE Transactions on Knowledge and Data Engineering
year: 2019
bibkey: florez2019learning
citations: 111
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.08542'}]
tags: [RAG, Few Shot, Reinforcement Learning, Datasets, Merging]
---
Humans excel in continuously learning with small data without forgetting how
to solve old problems. However, neural networks require large datasets to
compute latent representations across different tasks while minimizing a loss
function. For example, a natural language understanding (NLU) system will often
deal with emerging entities during its deployment as interactions with users in
realistic scenarios will generate new and infrequent names, events, and
locations. Here, we address this scenario by introducing an RL trainable
controller that disentangles the representation learning of a neural encoder
from its memory management role.
  Our proposed solution is straightforward and simple: we train a controller to
execute an optimal sequence of reading and writing operations on an external
memory with the goal of leveraging diverse activations from the past and
provide accurate predictions. Our approach is named Learning to Control (LTC)
and allows few-shot learning with two degrees of memory plasticity. We
experimentally show that our system obtains accurate results for few-shot
learning of entity recognition in the Stanford Task-Oriented Dialogue dataset.