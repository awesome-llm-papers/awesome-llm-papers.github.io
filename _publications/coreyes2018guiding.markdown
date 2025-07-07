---
layout: publication
title: Guiding Policies With Language Via Meta-learning
authors: John D. Co-reyes et al.
conference: Arxiv
year: 2018
citations: 38
bibkey: coreyes2018guiding
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1811.07882'}]
tags: [Reinforcement Learning, Agentic]
---
Behavioral skills or policies for autonomous agents are conventionally
learned from reward functions, via reinforcement learning, or from
demonstrations, via imitation learning. However, both modes of task
specification have their disadvantages: reward functions require manual
engineering, while demonstrations require a human expert to be able to actually
perform the task in order to generate the demonstration. Instruction following
from natural language instructions provides an appealing alternative: in the
same way that we can specify goals to other humans simply by speaking or
writing, we would like to be able to specify tasks for our machines. However, a
single instruction may be insufficient to fully communicate our intent or, even
if it is, may be insufficient for an autonomous agent to actually understand
how to perform the desired task. In this work, we propose an interactive
formulation of the task specification problem, where iterative language
corrections are provided to an autonomous agent, guiding it in acquiring the
desired skill. Our proposed language-guided policy learning algorithm can
integrate an instruction and a sequence of corrections to acquire new skills
very quickly. In our experiments, we show that this method can enable a policy
to follow instructions and corrections for simulated navigation and
manipulation tasks, substantially outperforming direct, non-interactive
instruction following.