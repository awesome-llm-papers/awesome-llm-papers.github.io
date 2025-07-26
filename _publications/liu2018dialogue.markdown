---
layout: publication
title: Dialogue Learning With Human Teaching And Feedback In End-to-end Trainable
  Task-oriented Dialogue Systems
authors: Bing Liu, Gokhan Tur, Dilek Hakkani-tur, Pararth Shah, Larry Heck
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 1
  (Long Papers)'
year: 2018
bibkey: liu2018dialogue
citations: 156
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1804.06512'}]
tags: ["NAACL", "Training Techniques"]
short_authors: Liu et al.
---
In this work, we present a hybrid learning method for training task-oriented
dialogue systems through online user interactions. Popular methods for learning
task-oriented dialogues include applying reinforcement learning with user
feedback on supervised pre-training models. Efficiency of such learning method
may suffer from the mismatch of dialogue state distribution between offline
training and online interactive learning stages. To address this challenge, we
propose a hybrid imitation and reinforcement learning method, with which a
dialogue agent can effectively learn from its interaction with users by
learning from human teaching and feedback. We design a neural network based
task-oriented dialogue agent that can be optimized end-to-end with the proposed
learning method. Experimental results show that our end-to-end dialogue agent
can learn effectively from the mistake it makes via imitation learning from
user teaching. Applying reinforcement learning with user feedback after the
imitation learning stage further improves the agent's capability in
successfully completing a task.