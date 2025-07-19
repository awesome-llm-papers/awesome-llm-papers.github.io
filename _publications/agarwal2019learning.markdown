---
layout: publication
title: Learning To Generalize From Sparse And Underspecified Rewards
authors: Agarwal et al.
conference: Proceedings of the 36th International Conference on Machine Learning PMLR
  97130-140 2019
year: 2019
bibkey: agarwal2019learning
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.07198'}]
tags: [Alt, Agentic, ICML, Efficiency And Optimization, Reinforcement Learning, Fine
    Tuning, Datasets]
---
We consider the problem of learning from sparse and underspecified rewards,
where an agent receives a complex input, such as a natural language
instruction, and needs to generate a complex response, such as an action
sequence, while only receiving binary success-failure feedback. Such
success-failure rewards are often underspecified: they do not distinguish
between purposeful and accidental success. Generalization from underspecified
rewards hinges on discounting spurious trajectories that attain accidental
success, while learning from sparse feedback requires effective exploration. We
address exploration by using a mode covering direction of KL divergence to
collect a diverse set of successful trajectories, followed by a mode seeking KL
divergence to train a robust policy. We propose Meta Reward Learning (MeRL) to
construct an auxiliary reward function that provides more refined feedback for
learning. The parameters of the auxiliary reward function are optimized with
respect to the validation performance of a trained policy. The MeRL approach
outperforms our alternative reward learning technique based on Bayesian
Optimization, and achieves the state-of-the-art on weakly-supervised semantic
parsing. It improves previous work by 1.2% and 2.4% on WikiTableQuestions and
WikiSQL datasets respectively.