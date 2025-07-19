---
layout: publication
title: 'Pseudo-recursal: Solving The Catastrophic Forgetting Problem In Deep Neural
  Networks'
authors: Atkinson et al.
conference: Arxiv
year: 2018
bibkey: atkinson2018pseudo
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1802.03875'}]
tags: [Security, Training Techniques, Datasets]
---
In general, neural networks are not currently capable of learning tasks in a
sequential fashion. When a novel, unrelated task is learnt by a neural network,
it substantially forgets how to solve previously learnt tasks. One of the
original solutions to this problem is pseudo-rehearsal, which involves learning
the new task while rehearsing generated items representative of the previous
task/s. This is very effective for simple tasks. However, pseudo-rehearsal has
not yet been successfully applied to very complex tasks because in these tasks
it is difficult to generate representative items. We accomplish
pseudo-rehearsal by using a Generative Adversarial Network to generate items so
that our deep network can learn to sequentially classify the CIFAR-10, SVHN and
MNIST datasets. After training on all tasks, our network loses only 1.67%
absolute accuracy on CIFAR-10 and gains 0.24% absolute accuracy on SVHN. Our
model's performance is a substantial improvement compared to the current state
of the art solution.