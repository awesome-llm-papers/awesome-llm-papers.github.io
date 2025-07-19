---
layout: publication
title: 'Llmthinkbench: Towards Basic Math Reasoning And Overthinking In Large Language
  Models'
authors: Srivastava et al.
conference: 'Findings of the Association for Computational Linguistics: ACL 2023'
year: 2025
bibkey: srivastava2025llmthinkbench
citations: 153
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2507.04023'}]
tags: [Model Architecture, Tools, Efficiency And Optimization, Evaluation, ACL, Transformer,
  Datasets, Reinforcement Learning, Alt]
---
Large Language Models (LLMs) have achieved remarkable performance on complex mathematical benchmarks, yet often struggle with simple arithmetic tasks and exhibit a tendency toward over-explaining or "overthinking" answers. To systematically assess this phenomenon, we introduce LLMThinkBench, a modular benchmarking framework that enables researchers to evaluate basic math reasoning and overthinking in LLMs. The framework provides 14 configurable math tasks with randomized test data generation and robust parsing strategies. Researchers can quantify overthinking using our Overthinking Score metric, which captures accuracy-verbosity tradeoffs through harmonic mean formulation. The tool offers flexible evaluation with a scalable vLLM/Transformers backend, multi-GPU support, and full configurability. Users can extend the tool with custom tasks, reproduce experiments with seeding, and generate detailed efficiency reports. Distributed as a pip-installable package with CLI and API access, LLMThinkBench provides researchers and practitioners an accessible, cost-effective alternative to expensive LLM-as-a-judge methods for diagnosing basic reasoning capabilities and efficiency analysis. Package can be installed as: pip install llmthinkbench