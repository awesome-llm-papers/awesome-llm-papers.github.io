---
layout: publication
title: Intrinsic Motivation And Automatic Curricula Via Asymmetric Self-play
authors: Sukhbaatar et al.
conference: Arxiv
year: 2017
bibkey: sukhbaatar2017intrinsic
citations: 142
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1703.05407'}]
tags: [Fine Tuning, Agentic, Reinforcement Learning, Training Techniques]
---
We describe a simple scheme that allows an agent to learn about its
environment in an unsupervised manner. Our scheme pits two versions of the same
agent, Alice and Bob, against one another. Alice proposes a task for Bob to
complete; and then Bob attempts to complete the task. In this work we will
focus on two kinds of environments: (nearly) reversible environments and
environments that can be reset. Alice will "propose" the task by doing a
sequence of actions and then Bob must undo or repeat them, respectively. Via an
appropriate reward structure, Alice and Bob automatically generate a curriculum
of exploration, enabling unsupervised training of the agent. When Bob is
deployed on an RL task within the environment, this unsupervised training
reduces the number of supervised episodes needed to learn, and in some cases
converges to a higher reward.