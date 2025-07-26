---
layout: publication
title: 'Web Agents With World Models: Learning And Leveraging Environment Dynamics
  In Web Navigation'
authors: Hyungjoo Chae, Namyoung Kim, Kai Tzu-iunn Ong, Minju Gwak, Gwanwoo Song,
  Jihoon Kim, Sunghwan Kim, Dongha Lee, Jinyoung Yeo
conference: No Venue
year: 2024
bibkey: chae2024web
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2410.13232'}]
tags: ["Agentic", "Efficiency", "Model Architecture", "Training Techniques"]
short_authors: Chae et al.
---
Large language models (LLMs) have recently gained much attention in building autonomous agents. However, the performance of current LLM-based web agents in long-horizon tasks is far from optimal, often yielding errors such as repeatedly buying a non-refundable flight ticket. By contrast, humans can avoid such an irreversible mistake, as we have an awareness of the potential outcomes (e.g., losing money) of our actions, also known as the "world model". Motivated by this, our study first starts with preliminary analyses, confirming the absence of world models in current LLMs (e.g., GPT-4o, Claude-3.5-Sonnet, etc.). Then, we present a World-model-augmented (WMA) web agent, which simulates the outcomes of its actions for better decision-making. To overcome the challenges in training LLMs as world models predicting next observations, such as repeated elements across observations and long HTML inputs, we propose a transition-focused observation abstraction, where the prediction objectives are free-form natural language descriptions exclusively highlighting important state differences between time steps. Experiments on WebArena and Mind2Web show that our world models improve agents' policy selection without training and demonstrate our agents' cost- and time-efficiency compared to recent tree-search-based agents.

https://huggingface.co/discussions/paper/6715f0358cb36b73b1dbf519