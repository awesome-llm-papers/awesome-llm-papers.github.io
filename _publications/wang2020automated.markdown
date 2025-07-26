---
layout: publication
title: Automated Concatenation Of Embeddings For Structured Prediction
authors: Xinyu Wang, Yong Jiang, Nguyen Bach, Tao Wang, Zhongqiang Huang, Fei Huang,
  Kewei Tu
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: wang2020automated
citations: 121
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.05006'}]
tags: ["Datasets", "Model Architecture", "Reinforcement Learning"]
short_authors: Wang et al.
---
Pretrained contextualized embeddings are powerful word representations for
structured prediction tasks. Recent work found that better word representations
can be obtained by concatenating different types of embeddings. However, the
selection of embeddings to form the best concatenated representation usually
varies depending on the task and the collection of candidate embeddings, and
the ever-increasing number of embedding types makes it a more difficult
problem. In this paper, we propose Automated Concatenation of Embeddings (ACE)
to automate the process of finding better concatenations of embeddings for
structured prediction tasks, based on a formulation inspired by recent progress
on neural architecture search. Specifically, a controller alternately samples a
concatenation of embeddings, according to its current belief of the
effectiveness of individual embedding types in consideration for a task, and
updates the belief based on a reward. We follow strategies in reinforcement
learning to optimize the parameters of the controller and compute the reward
based on the accuracy of a task model, which is fed with the sampled
concatenation as input and trained on a task dataset. Empirical results on 6
tasks and 21 datasets show that our approach outperforms strong baselines and
achieves state-of-the-art performance with fine-tuned embeddings in all the
evaluations.