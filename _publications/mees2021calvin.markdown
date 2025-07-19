---
layout: publication
title: 'CALVIN: A Benchmark For Language-conditioned Policy Learning For Long-horizon
  Robot Manipulation Tasks'
authors: Mees et al.
conference: IEEE Robotics and Automation Letters
year: 2021
bibkey: mees2021calvin
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.03227'}]
tags: [Agentic, Reinforcement Learning, Evaluation, Datasets]
---
General-purpose robots coexisting with humans in their environment must learn
to relate human language to their perceptions and actions to be useful in a
range of daily tasks. Moreover, they need to acquire a diverse repertoire of
general-purpose skills that allow composing long-horizon tasks by following
unconstrained language instructions. In this paper, we present CALVIN
(Composing Actions from Language and Vision), an open-source simulated
benchmark to learn long-horizon language-conditioned tasks. Our aim is to make
it possible to develop agents that can solve many robotic manipulation tasks
over a long horizon, from onboard sensors, and specified only via human
language. CALVIN tasks are more complex in terms of sequence length, action
space, and language than existing vision-and-language task datasets and
supports flexible specification of sensor suites. We evaluate the agents in
zero-shot to novel language instructions and to novel environments and objects.
We show that a baseline model based on multi-context imitation learning
performs poorly on CALVIN, suggesting that there is significant room for
developing innovative agents that learn to relate human language to their world
models with this benchmark.