---
layout: publication
title: Reward Augmented Maximum Likelihood For Neural Structured Prediction
authors: Norouzi et al.
conference: Arxiv
year: 2016
bibkey: norouzi2016reward
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1609.00150'}]
tags: [Efficiency And Optimization, Tools, Evaluation, Reinforcement Learning]
---
A key problem in structured output prediction is direct optimization of the
task reward function that matters for test evaluation. This paper presents a
simple and computationally efficient approach to incorporate task reward into a
maximum likelihood framework. By establishing a link between the log-likelihood
and expected reward objectives, we show that an optimal regularized expected
reward is achieved when the conditional distribution of the outputs given the
inputs is proportional to their exponentiated scaled rewards. Accordingly, we
present a framework to smooth the predictive probability of the outputs using
their corresponding rewards. We optimize the conditional log-probability of
augmented outputs that are sampled proportionally to their exponentiated scaled
rewards. Experiments on neural sequence to sequence models for speech
recognition and machine translation show notable improvements over a maximum
likelihood baseline by using reward augmented maximum likelihood (RAML), where
the rewards are defined as the negative edit distance between the outputs and
the ground truth labels.