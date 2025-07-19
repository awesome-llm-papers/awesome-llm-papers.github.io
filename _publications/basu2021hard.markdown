---
layout: publication
title: On Hard Episodes In Meta-learning
authors: Basu et al.
conference: IEEE Transactions on Pattern Analysis and Machine Intelligence
year: 2021
bibkey: basu2021hard
citations: 79
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.11190'}]
tags: [Security, Training Techniques, Evaluation, Few Shot, LLM for Code, RAG, Datasets,
  Reinforcement Learning]
---
Existing meta-learners primarily focus on improving the average task accuracy
across multiple episodes. Different episodes, however, may vary in hardness and
quality leading to a wide gap in the meta-learner's performance across
episodes. Understanding this issue is particularly critical in industrial
few-shot settings, where there is limited control over test episodes as they
are typically uploaded by end-users. In this paper, we empirically analyse the
behaviour of meta-learners on episodes of varying hardness across three
standard benchmark datasets: CIFAR-FS, mini-ImageNet, and tiered-ImageNet.
Surprisingly, we observe a wide gap in accuracy of around 50% between the
hardest and easiest episodes across all the standard benchmarks and
meta-learners. We additionally investigate various properties of hard episodes
and highlight their connection to catastrophic forgetting during meta-training.
To address the issue of sub-par performance on hard episodes, we investigate
and benchmark different meta-training strategies based on adversarial training
and curriculum learning. We find that adversarial training strategies are much
more powerful than curriculum learning in improving the prediction performance
on hard episodes.