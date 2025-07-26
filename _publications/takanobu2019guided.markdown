---
layout: publication
title: 'Guided Dialog Policy Learning: Reward Estimation For Multi-domain Task-oriented
  Dialog'
authors: Ryuichi Takanobu, Hanlin Zhu, Minlie Huang
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: takanobu2019guided
citations: 70
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.10719'}]
tags: ["EMNLP", "Reinforcement Learning"]
short_authors: Ryuichi Takanobu, Hanlin Zhu, Minlie Huang
---
Dialog policy decides what and how a task-oriented dialog system will
respond, and plays a vital role in delivering effective conversations. Many
studies apply Reinforcement Learning to learn a dialog policy with the reward
function which requires elaborate design and pre-specified user goals. With the
growing needs to handle complex goals across multiple domains, such manually
designed reward functions are not affordable to deal with the complexity of
real-world tasks. To this end, we propose Guided Dialog Policy Learning, a
novel algorithm based on Adversarial Inverse Reinforcement Learning for joint
reward estimation and policy optimization in multi-domain task-oriented dialog.
The proposed approach estimates the reward signal and infers the user goal in
the dialog sessions. The reward estimator evaluates the state-action pairs so
that it can guide the dialog policy at each dialog turn. Extensive experiments
on a multi-domain dialog dataset show that the dialog policy guided by the
learned reward function achieves remarkably higher task success than
state-of-the-art baselines.