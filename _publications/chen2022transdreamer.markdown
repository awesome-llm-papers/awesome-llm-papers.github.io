---
layout: publication
title: 'Transdreamer: Reinforcement Learning With Transformer World Models'
authors: Chen et al.
conference: Neural Networks
year: 2022
bibkey: chen2022transdreamer
citations: 289
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.09481'}]
tags: [RAG, Training Techniques, ICANN, Agentic, Tools, Transformer, Model Architecture,
  Efficiency And Optimization, Reinforcement Learning]
---
The Dreamer agent provides various benefits of Model-Based Reinforcement
Learning (MBRL) such as sample efficiency, reusable knowledge, and safe
planning. However, its world model and policy networks inherit the limitations
of recurrent neural networks and thus an important question is how an MBRL
framework can benefit from the recent advances of transformers and what the
challenges are in doing so. In this paper, we propose a transformer-based MBRL
agent, called TransDreamer. We first introduce the Transformer State-Space
Model, a world model that leverages a transformer for dynamics predictions. We
then share this world model with a transformer-based policy network and obtain
stability in training a transformer-based RL agent. In experiments, we apply
the proposed model to 2D visual RL and 3D first-person visual RL tasks both
requiring long-range memory access for memory-based reasoning. We show that the
proposed model outperforms Dreamer in these complex tasks.