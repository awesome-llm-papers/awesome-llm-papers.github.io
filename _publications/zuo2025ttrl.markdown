---
layout: publication
title: 'TTRL: Test-time Reinforcement Learning'
authors: Zuo et al.
conference: IEEE Transactions on Software Engineering
year: 2025
bibkey: zuo2025ttrl
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.16084'}]
tags: [Training Techniques, LLM For Code, Agentic, LLM for Code, Reinforcement Learning,
  Alt]
---
This paper investigates Reinforcement Learning (RL) on data without explicit labels for reasoning tasks in Large Language Models (LLMs). The core challenge of the problem is reward estimation during inference while not having access to ground-truth information. While this setting appears elusive, we find that common practices in Test-Time Scaling (TTS), such as majority voting, yield surprisingly effective rewards suitable for driving RL training. In this work, we introduce Test-Time Reinforcement Learning (TTRL), a novel method for training LLMs using RL on unlabeled data. TTRL enables self-evolution of LLMs by utilizing the priors in the pre-trained models. Our experiments demonstrate that TTRL consistently improves performance across a variety of tasks and models. Notably, TTRL boosts the pass@1 performance of Qwen-2.5-Math-7B by approximately 211% on the AIME 2024 with only unlabeled test data. Furthermore, although TTRL is only supervised by the maj@n metric, TTRL has demonstrated performance to consistently surpass the upper limit of the initial model maj@n, and approach the performance of models trained directly on test data with ground-truth labels. Our experimental findings validate the general effectiveness of TTRL across various tasks and highlight TTRL's potential for broader tasks and domains. GitHub: https://github.com/PRIME-RL/TTRL