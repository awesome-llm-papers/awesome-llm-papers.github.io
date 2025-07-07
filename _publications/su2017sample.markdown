---
layout: publication
title: Sample-efficient Actor-critic Reinforcement Learning With Supervised Data For
  Dialogue Management
authors: Pei-hao Su, Pawel Budzianowski, Stefan Ultes, Milica Gasic, Steve Young
conference: Arxiv
year: 2017
citations: 34
bibkey: su2017sample
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1707.00130'}]
tags: [Efficiency and Optimization, Reinforcement Learning, Agentic]
---
Deep reinforcement learning (RL) methods have significant potential for
dialogue policy optimisation. However, they suffer from a poor performance in
the early stages of learning. This is especially problematic for on-line
learning with real users. Two approaches are introduced to tackle this problem.
Firstly, to speed up the learning process, two sample-efficient neural networks
algorithms: trust region actor-critic with experience replay (TRACER) and
episodic natural actor-critic with experience replay (eNACER) are presented.
For TRACER, the trust region helps to control the learning step size and avoid
catastrophic model changes. For eNACER, the natural gradient identifies the
steepest ascent direction in policy space to speed up the convergence. Both
models employ off-policy learning with experience replay to improve
sample-efficiency. Secondly, to mitigate the cold start issue, a corpus of
demonstration data is utilised to pre-train the models prior to on-line
reinforcement learning. Combining these two approaches, we demonstrate a
practical approach to learn deep RL-based dialogue policies and demonstrate
their effectiveness in a task-oriented information seeking domain.