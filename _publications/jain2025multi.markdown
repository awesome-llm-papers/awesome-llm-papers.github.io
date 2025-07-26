---
layout: publication
title: Multi-turn Code Generation Through Single-step Rewards
authors: Arnav Kumar Jain, Gonzalo Gonzalez-pumariega, Wayne Chen, Alexander M Rush,
  Wenting Zhao, Sanjiban Choudhury
conference: No Venue
year: 2025
bibkey: jain2025multi
additional_links: [{name: Code, url: 'https://github.com/portal-cornell/muCode'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67c34e3ceae05d8f94f8010e'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.20380'}]
tags: ["Llm For Code", "Reinforcement Learning"]
short_authors: Jain et al.
---
We address the problem of code generation from multi-turn execution feedback. Existing methods either generate code without feedback or use complex, hierarchical reinforcement learning to optimize multi-turn rewards. We propose a simple yet scalable approach, muCode, that solves multi-turn code generation using only single-step rewards. Our key insight is that code generation is a one-step recoverable MDP, where the correct code can be recovered from any intermediate code state in a single turn. muCode iteratively trains both a generator to provide code solutions conditioned on multi-turn execution feedback and a verifier to score the newly generated code. Experimental evaluations show that our approach achieves significant improvements over the state-of-the-art baselines. We provide analysis of the design choices of the reward models and policy, and show the efficacy of muCode at utilizing the execution feedback. Our code is available at https://github.com/portal-cornell/muCode.

https://huggingface.co/discussions/paper/67c34e3ceae05d8f94f8010e