---
layout: publication
title: Large-scale Interactive Recommendation With Tree-structured Policy Gradient
authors: Chen et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2018
bibkey: chen2018large
citations: 122
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1811.05869'}]
tags: [Agentic, Tools, Efficiency And Optimization, Reinforcement Learning, AAAI,
  Datasets]
---
Reinforcement learning (RL) has recently been introduced to interactive
recommender systems (IRS) because of its nature of learning from dynamic
interactions and planning for long-run performance. As IRS is always with
thousands of items to recommend (i.e., thousands of actions), most existing
RL-based methods, however, fail to handle such a large discrete action space
problem and thus become inefficient. The existing work that tries to deal with
the large discrete action space problem by utilizing the deep deterministic
policy gradient framework suffers from the inconsistency between the continuous
action representation (the output of the actor network) and the real discrete
action. To avoid such inconsistency and achieve high efficiency and
recommendation effectiveness, in this paper, we propose a Tree-structured
Policy Gradient Recommendation (TPGR) framework, where a balanced hierarchical
clustering tree is built over the items and picking an item is formulated as
seeking a path from the root to a certain leaf of the tree. Extensive
experiments on carefully-designed environments based on two real-world datasets
demonstrate that our model provides superior recommendation performance and
significant efficiency improvement over state-of-the-art methods.