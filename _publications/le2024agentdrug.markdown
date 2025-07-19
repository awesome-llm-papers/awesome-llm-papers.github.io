---
layout: publication
title: 'Agentdrug: Utilizing Large Language Models In An Agentic Workflow For Zero-shot
  Molecular Optimization'
authors: Le Khiem, Hua Ting, Chawla Nitesh V.
conference: Proceedings of the 32nd ACM International Conference on Information and
  Knowledge Management
year: 2024
bibkey: le2024agentdrug
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.13147'}]
tags: [RAG, Prompting, Agentic, Evaluation, CIKM, Efficiency And Optimization, Datasets]
---
Molecular optimization -- modifying a given molecule to improve desired properties -- is a fundamental task in drug discovery. While LLMs hold the potential to solve this task using natural language to drive the optimization, straightforward prompting achieves limited accuracy. In this work, we propose AgentDrug, an agentic workflow that leverages LLMs in a structured refinement process to achieve significantly higher accuracy. AgentDrug defines a nested refinement loop: the inner loop uses feedback from cheminformatics toolkits to validate molecular structures, while the outer loop guides the LLM with generic feedback and a gradient-based objective to steer the molecule toward property improvement. We evaluate AgentDrug on benchmarks with both single- and multi-property optimization under loose and strict thresholds. Results demonstrate significant performance gains over previous methods. With Qwen-2.5-3B, AgentDrug improves accuracy by 20.7% (loose) and 16.8% (strict) on six single-property tasks, and by 7.0% and 5.3% on eight multi-property tasks. With larger model Qwen-2.5-7B, AgentDrug further improves accuracy on 6 single-property objectives by 28.9% (loose) and 29.0% (strict), and on 8 multi-property objectives by 14.9% (loose) and 13.2% (strict).