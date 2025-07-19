---
layout: publication
title: 'When Transformers Meet Recommenders: Integrating Self-attentive Sequential
  Recommendation With Fine-tuned Llms'
authors: Liu Kechen
conference: 2018 IEEE International Conference on Data Mining (ICDM)
year: 2025
bibkey: liu2025when
citations: 1704
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2507.05733'}]
tags: [RAG, Training Techniques, Attention Mechanism, Prompting, Tools, Transformer,
  Model Architecture, Fine Tuning, Datasets]
---
Self-Attentive Sequential Recommendation (SASRec) effectively captures long-term user preferences by applying attention mechanisms to historical interactions. Concurrently, the rise of Large Language Models (LLMs) has motivated research into LLM-based recommendation, which leverages their powerful generalization and language understanding capabilities. However, LLMs often lack the domain-specific knowledge and collaborative signals essential for high-quality recommendations when relying solely on textual prompts. To address this limitation, this study proposes SASRecLLM, a novel framework that integrates SASRec as a collaborative encoder with an LLM fine-tuned using Low-Rank Adaptation (LoRA). The components are connected via a mapping layer to align their dimensional spaces, and three targeted training strategies are designed to optimize the hybrid architecture. Extensive experiments on multiple datasets demonstrate that SASRecLLM achieves robust and consistent improvements over strong baselines in both cold-start and warm-start scenarios. This work advances the field of LLM-based recommendation by presenting a modular and effective paradigm for fusing structured collaborative filtering with the semantic power of fine-tuned LLMs. The implementation is available on GitHub: https://github.com/kechenkristin/RecLLM