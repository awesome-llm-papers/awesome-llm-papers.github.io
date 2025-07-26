---
layout: publication
title: Policy Networks With Two-stage Training For Dialogue Systems
authors: Mehdi Fatemi, Layla El Asri, Hannes Schulz, Jing He, Kaheer Suleman
conference: Proceedings of the 17th Annual Meeting of the Special Interest Group on
  Discourse and Dialogue
year: 2016
bibkey: fatemi2016policy
citations: 70
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.03152'}]
tags: ["Model Architecture", "Reinforcement Learning", "Training Techniques"]
short_authors: Fatemi et al.
---
In this paper, we propose to use deep policy networks which are trained with
an advantage actor-critic method for statistically optimised dialogue systems.
First, we show that, on summary state and action spaces, deep Reinforcement
Learning (RL) outperforms Gaussian Processes methods. Summary state and action
spaces lead to good performance but require pre-engineering effort, RL
knowledge, and domain expertise. In order to remove the need to define such
summary spaces, we show that deep RL can also be trained efficiently on the
original state and action spaces. Dialogue systems based on partially
observable Markov decision processes are known to require many dialogues to
train, which makes them unappealing for practical deployment. We show that a
deep RL method based on an actor-critic architecture can exploit a small amount
of data very efficiently. Indeed, with only a few hundred dialogues collected
with a handcrafted policy, the actor-critic deep learner is considerably
bootstrapped from a combination of supervised and batch RL. In addition,
convergence to an optimal policy is significantly sped up compared to other
deep RL methods initialized on the data with batch RL. All experiments are
performed on a restaurant domain derived from the Dialogue State Tracking
Challenge 2 (DSTC2) dataset.