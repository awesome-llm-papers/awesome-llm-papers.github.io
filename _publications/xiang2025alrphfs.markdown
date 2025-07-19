---
layout: publication
title: 'ALRPHFS: Adversarially Learned Risk Patterns With Hierarchical Fast \& Slow
  Reasoning For Robust Agent Defense'
authors: Xiang Shiyu, Zhang Tong, Chen Ronghao
conference: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: xiang2025alrphfs
citations: 95
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.19260'}]
tags: [RAG, Training Techniques, Agentic, Tools, CVPR, Efficiency And Optimization,
  Reinforcement Learning, Security, Responsible AI]
---
LLM Agents are becoming central to intelligent systems. However, their deployment raises serious safety concerns. Existing defenses largely rely on "Safety Checks", which struggle to capture the complex semantic risks posed by harmful user inputs or unsafe agent behaviors - creating a significant semantic gap between safety checks and real-world risks. To bridge this gap, we propose a novel defense framework, ALRPHFS (Adversarially Learned Risk Patterns with Hierarchical Fast & Slow Reasoning). ALRPHFS consists of two core components: (1) an offline adversarial self-learning loop to iteratively refine a generalizable and balanced library of risk patterns, substantially enhancing robustness without retraining the base LLM, and (2) an online hierarchical fast & slow reasoning engine that balances detection effectiveness with computational efficiency. Experimental results demonstrate that our approach achieves superior overall performance compared to existing baselines, achieving a best-in-class average accuracy of 80% and exhibiting strong generalizability across agents and tasks.