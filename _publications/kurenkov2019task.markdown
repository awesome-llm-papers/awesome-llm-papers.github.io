---
layout: publication
title: Task-oriented Language Grounding For Language Input With Multiple Sub-goals
  Of Non-linear Order
authors: Kurenkov Vladislav, Maksudov Bulat, Khan Adil
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2019
bibkey: kurenkov2019task
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.12354'}]
tags: [Attention Mechanism, Agentic, Model Architecture, Reinforcement Learning, AAAI]
---
In this work, we analyze the performance of general deep reinforcement
learning algorithms for a task-oriented language grounding problem, where
language input contains multiple sub-goals and their order of execution is
non-linear.
  We generate a simple instructional language for the GridWorld environment,
that is built around three language elements (order connectors) defining the
order of execution: one linear - "comma" and two non-linear - "but first", "but
before". We apply one of the deep reinforcement learning baselines - Double DQN
with frame stacking and ablate several extensions such as Prioritized
Experience Replay and Gated-Attention architecture.
  Our results show that the introduction of non-linear order connectors
improves the success rate on instructions with a higher number of sub-goals in
2-3 times, but it still does not exceed 20%. Also, we observe that the usage of
Gated-Attention provides no competitive advantage against concatenation in this
setting. Source code and experiments' results are available at
https://github.com/vkurenkov/language-grounding-multigoal