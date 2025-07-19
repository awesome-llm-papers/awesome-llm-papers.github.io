---
layout: publication
title: Decoupling Exploration And Exploitation For Meta-reinforcement Learning Without
  Sacrifices
authors: Liu et al.
conference: Neural Networks
year: 2020
bibkey: liu2020decoupling
citations: 158
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2008.02790'}]
tags: [RAG, Training Techniques, ICANN, Agentic, Reinforcement Learning, Fine Tuning]
---
The goal of meta-reinforcement learning (meta-RL) is to build agents that can
quickly learn new tasks by leveraging prior experience on related tasks.
Learning a new task often requires both exploring to gather task-relevant
information and exploiting this information to solve the task. In principle,
optimal exploration and exploitation can be learned end-to-end by simply
maximizing task performance. However, such meta-RL approaches struggle with
local optima due to a chicken-and-egg problem: learning to explore requires
good exploitation to gauge the exploration's utility, but learning to exploit
requires information gathered via exploration. Optimizing separate objectives
for exploration and exploitation can avoid this problem, but prior meta-RL
exploration objectives yield suboptimal policies that gather information
irrelevant to the task. We alleviate both concerns by constructing an
exploitation objective that automatically identifies task-relevant information
and an exploration objective to recover only this information. This avoids
local optima in end-to-end training, without sacrificing optimal exploration.
Empirically, DREAM substantially outperforms existing approaches on complex
meta-RL problems, such as sparse-reward 3D visual navigation. Videos of DREAM:
https://ezliu.github.io/dream/