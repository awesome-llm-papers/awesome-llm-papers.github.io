---
layout: publication
title: 'AIDE: Agentically Improve Visual Language Model With Domain Experts'
authors: Chiu et al.
conference: Journal of Visual Languages &amp; Computing
year: 2025
bibkey: chiu2025aide
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.09051'}]
tags: [RAG, Training Techniques, Distillation, Agentic, Tools, Evaluation, Efficiency
    And Optimization, Reinforcement Learning, Datasets]
---
The enhancement of Visual Language Models (VLMs) has traditionally relied on
knowledge distillation from larger, more capable models. This dependence
creates a fundamental bottleneck for improving state-of-the-art systems,
particularly when no superior models exist. We introduce AIDE (Agentic
Improvement through Domain Experts), a novel framework that enables VLMs to
autonomously enhance their capabilities by leveraging specialized domain expert
models. AIDE operates through a four-stage process: (1) identifying instances
for refinement, (2) engaging domain experts for targeted analysis, (3)
synthesizing expert outputs with existing data, and (4) integrating enhanced
instances into the training pipeline. Experiments on multiple benchmarks,
including MMMU, MME, MMBench, etc., demonstrate AIDE's ability to achieve
notable performance gains without relying on larger VLMs nor human supervision.
Our framework provides a scalable, resource-efficient approach to continuous
VLM improvement, addressing critical limitations in current methodologies,
particularly valuable when larger models are unavailable to access.