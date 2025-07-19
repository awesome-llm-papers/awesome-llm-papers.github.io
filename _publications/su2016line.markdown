---
layout: publication
title: On-line Active Reward Learning For Policy Optimisation In Spoken Dialogue Systems
authors: Su et al.
conference: 'Proceedings of the 54th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2016
bibkey: su2016line
citations: 102
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1605.07669'}]
tags: [Tools, ACL, Agentic, Applications, Reinforcement Learning]
---
The ability to compute an accurate reward function is essential for
optimising a dialogue policy via reinforcement learning. In real-world
applications, using explicit user feedback as the reward signal is often
unreliable and costly to collect. This problem can be mitigated if the user's
intent is known in advance or data is available to pre-train a task success
predictor off-line. In practice neither of these apply for most real world
applications. Here we propose an on-line learning framework whereby the
dialogue policy is jointly trained alongside the reward model via active
learning with a Gaussian process model. This Gaussian process operates on a
continuous space dialogue representation generated in an unsupervised fashion
using a recurrent neural network encoder-decoder. The experimental results
demonstrate that the proposed framework is able to significantly reduce data
annotation costs and mitigate noisy user feedback in dialogue policy learning.