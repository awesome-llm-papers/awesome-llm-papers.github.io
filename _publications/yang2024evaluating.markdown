---
layout: publication
title: Evaluating World Models With LLM For Decision Making
authors: Yang et al.
conference: The European Union Decides
year: 2024
bibkey: yang2024evaluating
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.08794'}]
tags: [RAG, GPT, Agentic, Evaluation, Model Architecture, Reinforcement Learning]
---
World model emerges as a key module in decision making, where MuZero and
Dreamer achieve remarkable successes in complex tasks. Recent work leverages
Large Language Models (LLMs) as general world simulators to simulate the
dynamics of the world due to their generalizability. LLMs also serve as the
world model for deliberative reasoning in Reasoning via Planning (RAP) and Tree
of Thought (ToT). However, the world models are either evaluated as a general
world simulator, or as a functional module of the agent, i.e., predicting the
transitions to assist the planning. In this work, we propose a comprehensive
evaluation of the world models with LLMs from the decision making perspective.
Specifically, we leverage the 31 diverse environments from (Wang et al.,
2023;2024) and curate the rule-based policy of each environment for the diverse
evaluation. Then, we design three main tasks, i.e., policy verification, action
proposal, and policy planning, where the world models can be used for decision
making solely. Finally, we conduct the comprehensive evaluation of the advanced
LLMs, i.e., GPT-4o and GPT-4o-mini, on the environments for the three main
tasks under various settings. The key observations include: i) GPT-4o
significantly outperforms GPT-4o-mini on the three main tasks, especially for
the tasks which require the domain knowledge, ii) the performance of the world
model with LLM will be decreased for long-term decision-making tasks, and iii)
the combination of different functionalities of the world model will brings
additional unstabilities of the performance.