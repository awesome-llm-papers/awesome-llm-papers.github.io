---
layout: publication
title: Strategy-augmented Planning For Large Language Models Via Opponent Exploitation
authors: Xu et al.
conference: 4th ACM International Conference on AI in Finance
year: 2025
bibkey: xu2025strategy
citations: 89
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.08459'}]
tags: [Training Techniques, Prompting, Agentic, Tools, Evaluation, Reinforcement Learning,
  Security, UAI]
---
Efficiently modeling and exploiting opponents is a long-standing challenge in adversarial domains. Large Language Models (LLMs) trained on extensive textual data have recently demonstrated outstanding performance in general tasks, introducing new research directions for opponent modeling. Some studies primarily focus on directly using LLMs to generate decisions based on the elaborate prompt context that incorporates opponent descriptions, while these approaches are limited to scenarios where LLMs possess adequate domain expertise. To address that, we introduce a two-stage Strategy-Augmented Planning (SAP) framework that significantly enhances the opponent exploitation capabilities of LLM-based agents by utilizing a critical component, the Strategy Evaluation Network (SEN). Specifically, in the offline stage, we construct an explicit strategy space and subsequently collect strategy-outcome pair data for training the SEN network. During the online phase, SAP dynamically recognizes the opponent's strategies and greedily exploits them by searching best response strategy on the well-trained SEN, finally translating strategy to a course of actions by carefully designed prompts. Experimental results show that SAP exhibits robust generalization capabilities, allowing it to perform effectively not only against previously encountered opponent strategies but also against novel, unseen strategies. In the MicroRTS environment, SAP achieves a \\(85.35%\\) performance improvement over baseline methods and matches the competitiveness of reinforcement learning approaches against state-of-the-art (SOTA) rule-based AI. Our code is available at https://github.com/hsushuai/SAP.