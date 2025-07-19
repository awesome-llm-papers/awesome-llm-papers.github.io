---
layout: publication
title: 'Arch-router: Aligning LLM Routing With Human Preferences'
authors: Tran et al.
conference: Proceedings of the 37th Annual ACM Symposium on User Interface Software
  and Technology
year: 2025
bibkey: tran2025arch
citations: 55
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.16655'}]
tags: [Training Techniques, Tools, Evaluation, Reinforcement Learning, Datasets]
---
With the rapid proliferation of large language models (LLMs) -- each optimized for different strengths, style, or latency/cost profile -- routing has become an essential technique to operationalize the use of different models. However, existing LLM routing approaches are limited in two key ways: they evaluate performance using benchmarks that often fail to capture human preferences driven by subjective evaluation criteria, and they typically select from a limited pool of models. In this work, we propose a preference-aligned routing framework that guides model selection by matching queries to user-defined domains (e.g., travel) or action types (e.g., image editing) -- offering a practical mechanism to encode preferences in routing decisions. Specifically, we introduce \textbf\{Arch-Router\}, a compact 1.5B model that learns to map queries to domain-action preferences for model routing decisions. Our approach also supports seamlessly adding new models for routing without requiring retraining or architectural modifications. Experiments on conversational datasets demonstrate that our approach achieves state-of-the-art (SOTA) results in matching queries with human preferences, outperforming top proprietary models. Our approach captures subjective evaluation criteria and makes routing decisions more transparent and flexible. Our model is available at: \texttt\{https://huggingface.co/katanemo/Arch-Router-1.5B\}.