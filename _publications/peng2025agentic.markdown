---
layout: publication
title: 'Agentic Reward Modeling: Integrating Human Preferences With Verifiable Correctness
  Signals For Reliable Reward Systems'
authors: Peng et al.
conference: 'Robotics: Science and Systems XV'
year: 2025
bibkey: peng2025agentic
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.19328'}]
tags: [Training Techniques, Agentic, Evaluation, RSS, Reinforcement Learning, Datasets]
---
Reward models (RMs) are crucial for the training and inference-time scaling
up of large language models (LLMs). However, existing reward models primarily
focus on human preferences, neglecting verifiable correctness signals which
have shown strong potential in training LLMs. In this paper, we propose agentic
reward modeling, a reward system that combines reward models with verifiable
correctness signals from different aspects to provide reliable rewards. We
empirically implement a reward agent, named RewardAgent, that combines human
preference rewards with two verifiable signals: factuality and instruction
following, to provide more reliable rewards. We conduct comprehensive
experiments on existing reward model benchmarks and inference time best-of-n
searches on real-world downstream tasks. RewardAgent significantly outperforms
vanilla reward models, demonstrating its effectiveness. We further construct
training preference pairs using RewardAgent and train an LLM with the DPO
objective, achieving superior performance on various NLP benchmarks compared to
conventional reward models. Our codes are publicly released to facilitate
further research (https://github.com/THU-KEG/Agentic-Reward-Modeling).