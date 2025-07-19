---
layout: publication
title: Reward Reasoning Model
authors: Guo et al.
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2025
bibkey: guo2025reward
citations: 201
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.14674'}]
tags: [RAG, EMNLP, Training Techniques, Agentic, Tools, Evaluation, Reinforcement
    Learning, Datasets]
---
Reward models play a critical role in guiding large language models toward outputs that align with human expectations. However, an open challenge remains in effectively utilizing test-time compute to enhance reward model performance. In this work, we introduce Reward Reasoning Models (RRMs), which are specifically designed to execute a deliberate reasoning process before generating final rewards. Through chain-of-thought reasoning, RRMs leverage additional test-time compute for complex queries where appropriate rewards are not immediately apparent. To develop RRMs, we implement a reinforcement learning framework that fosters self-evolved reward reasoning capabilities without requiring explicit reasoning traces as training data. Experimental results demonstrate that RRMs achieve superior performance on reward modeling benchmarks across diverse domains. Notably, we show that RRMs can adaptively exploit test-time compute to further improve reward accuracy. The pretrained reward reasoning models are available at https://huggingface.co/Reward-Reasoning.