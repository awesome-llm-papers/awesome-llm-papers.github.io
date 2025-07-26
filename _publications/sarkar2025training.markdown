---
layout: publication
title: Training Language Models For Social Deduction With Multi-agent Reinforcement
  Learning
authors: Bidipta Sarkar, Warren Xia, C. Karen Liu, Dorsa Sadigh
conference: No Venue
year: 2025
bibkey: sarkar2025training
additional_links: [{name: Code, url: 'https://socialdeductionllm.github.io/'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/67ab1315385da1f07cda12a5'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2502.06060'}]
tags: ["Reinforcement Learning", "Training Techniques"]
short_authors: Sarkar et al.
---
Communicating in natural language is a powerful tool in multi-agent settings, as it enables independent agents to share information in partially observable settings and allows zero-shot coordination with humans. However, most prior works are limited as they either rely on training with large amounts of human demonstrations or lack the ability to generate natural and useful communication strategies. In this work, we train language models to have productive discussions about their environment in natural language without any human demonstrations. We decompose the communication problem into listening and speaking. Our key idea is to leverage the agent's goal to predict useful information about the world as a dense reward signal that guides communication. Specifically, we improve a model's listening skills by training them to predict information about the environment based on discussions, and we simultaneously improve a model's speaking skills with multi-agent reinforcement learning by rewarding messages based on their influence on other agents. To investigate the role and necessity of communication in complex social settings, we study an embodied social deduction game based on Among Us, where the key question to answer is the identity of an adversarial imposter. We analyze emergent behaviors due to our technique, such as accusing suspects and providing evidence, and find that it enables strong discussions, doubling the win rates compared to standard RL. We release our code and models at https://socialdeductionllm.github.io/

https://huggingface.co/discussions/paper/67ab1315385da1f07cda12a5