---
layout: publication
title: 'Look Before You Leap: Bridging Model-free And Model-based Reinforcement Learning
  For Planned-ahead Vision-and-language Navigation'
authors: Xin Wang, Wenhan Xiong, Hongmin Wang, William Yang Wang
conference: Lecture Notes in Computer Science
year: 2018
bibkey: wang2018look
citations: 194
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1803.07729'}]
tags: ["Reinforcement Learning"]
short_authors: Wang et al.
---
Existing research studies on vision and language grounding for robot
navigation focus on improving model-free deep reinforcement learning (DRL)
models in synthetic environments. However, model-free DRL models do not
consider the dynamics in the real-world environments, and they often fail to
generalize to new scenes. In this paper, we take a radical approach to bridge
the gap between synthetic studies and real-world practices---We propose a
novel, planned-ahead hybrid reinforcement learning model that combines
model-free and model-based reinforcement learning to solve a real-world
vision-language navigation task. Our look-ahead module tightly integrates a
look-ahead policy model with an environment model that predicts the next state
and the reward. Experimental results suggest that our proposed method
significantly outperforms the baselines and achieves the best on the real-world
Room-to-Room dataset. Moreover, our scalable method is more generalizable when
transferring to unseen environments.