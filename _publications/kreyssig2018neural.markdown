---
layout: publication
title: Neural User Simulation For Corpus-based Policy Optimisation For Spoken Dialogue
  Systems
authors: Kreyssig et al.
conference: Proceedings of the 19th Annual SIGdial Meeting on Discourse and Dialogue
year: 2018
bibkey: kreyssig2018neural
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.06966'}]
tags: [Training Techniques, Agentic, Tools, Evaluation, Reinforcement Learning, Datasets]
---
User Simulators are one of the major tools that enable offline training of
task-oriented dialogue systems. For this task the Agenda-Based User Simulator
(ABUS) is often used. The ABUS is based on hand-crafted rules and its output is
in semantic form. Issues arise from both properties such as limited diversity
and the inability to interface a text-level belief tracker. This paper
introduces the Neural User Simulator (NUS) whose behaviour is learned from a
corpus and which generates natural language, hence needing a less labelled
dataset than simulators generating a semantic output. In comparison to much of
the past work on this topic, which evaluates user simulators on corpus-based
metrics, we use the NUS to train the policy of a reinforcement learning based
Spoken Dialogue System. The NUS is compared to the ABUS by evaluating the
policies that were trained using the simulators. Cross-model evaluation is
performed i.e. training on one simulator and testing on the other. Furthermore,
the trained policies are tested on real users. In both evaluation tasks the NUS
outperformed the ABUS.