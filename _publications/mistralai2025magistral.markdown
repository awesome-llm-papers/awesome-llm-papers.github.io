---
layout: publication
title: Magistral
authors: Mistral-ai et al.
conference: Viruses
year: 2025
bibkey: mistralai2025magistral
citations: 280
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.10910'}]
tags: [Multimodal Models, Agentic, Reinforcement Learning, Training Techniques]
---
We introduce Magistral, Mistral's first reasoning model and our own scalable reinforcement learning (RL) pipeline. Instead of relying on existing implementations and RL traces distilled from prior models, we follow a ground up approach, relying solely on our own models and infrastructure. Notably, we demonstrate a stack that enabled us to explore the limits of pure RL training of LLMs, present a simple method to force the reasoning language of the model, and show that RL on text data alone maintains most of the initial checkpoint's capabilities. We find that RL on text maintains or improves multimodal understanding, instruction following and function calling. We present Magistral Medium, trained for reasoning on top of Mistral Medium 3 with RL alone, and we open-source Magistral Small (Apache 2.0) which further includes cold-start data from Magistral Medium.