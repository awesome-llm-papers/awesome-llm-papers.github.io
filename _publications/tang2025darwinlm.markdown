---
layout: publication
title: 'Darwinlm: Evolutionary Structured Pruning Of Large Language Models'
authors: Tang et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2025
bibkey: tang2025darwinlm
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.07780'}]
tags: [Training Techniques, EMNLP, Efficiency And Optimization, Reinforcement Learning,
  Applications, Quantization, Pruning]
---
Large Language Models (LLMs) have achieved significant success across various
NLP tasks. However, their massive computational costs limit their widespread
use, particularly in real-time applications. Structured pruning offers an
effective solution by compressing models and directly providing end-to-end
speed improvements, regardless of the hardware environment. Meanwhile,
different components of the model exhibit varying sensitivities towards
pruning, calling for non-uniform model compression. However, a pruning method
should not only identify a capable substructure, but also account for
post-compression training. To this end, we propose DarwinLM, a method for
training-aware structured pruning. DarwinLM builds upon an evolutionary search
process, generating multiple offspring models in each generation through
mutation, and selecting the fittest for survival. To assess the effect of
post-training, we incorporate a lightweight, multistep training process within
the offspring population, progressively increasing the number of tokens and
eliminating poorly performing models in each selection stage. We validate our
method through extensive experiments on Llama-2-7B, Llama-3.1-8B and
Qwen-2.5-14B-Instruct, achieving state-of-the-art performance for structured
pruning. For instance, DarwinLM surpasses ShearedLlama while requiring 5x less
training data during post-compression training. Code is at:
https://github.com/IST-DASLab/DarwinLM