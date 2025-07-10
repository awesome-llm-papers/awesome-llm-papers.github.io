---
layout: publication
title: Human Instruction-following With Deep Reinforcement Learning Via Transfer-learning
  From Text
authors: Felix Hill, Sona Mokra, Nathaniel Wong, Tim Harley
conference: Arxiv
year: 2020
citations: 36
bibkey: hill2020human
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.09382'}]
tags: [Model Architecture, Reinforcement Learning, Training Techniques, Agentic, BERT]
---
Recent work has described neural-network-based agents that are trained with
reinforcement learning (RL) to execute language-like commands in simulated
worlds, as a step towards an intelligent agent or robot that can be instructed
by human users. However, the optimisation of multi-goal motor policies via deep
RL from scratch requires many episodes of experience. Consequently,
instruction-following with deep RL typically involves language generated from
templates (by an environment simulator), which does not reflect the varied or
ambiguous expressions of real users. Here, we propose a conceptually simple
method for training instruction-following agents with deep RL that are robust
to natural human instructions. By applying our method with a state-of-the-art
pre-trained text-based language model (BERT), on tasks requiring agents to
identify and position everyday objects relative to other objects in a
naturalistic 3D simulated room, we demonstrate substantially-above-chance
zero-shot transfer from synthetic template commands to natural instructions
given by humans. Our approach is a general recipe for training any deep
RL-based system to interface with human users, and bridges the gap between two
research directions of notable recent success: agent-centric motor behavior and
text-based representation learning.