---
layout: publication
title: Coordinating Search-informed Reasoning And Reasoning-guided Search In Claim
  Verification
authors: Hu Qisheng, Long Quanyu, Wang Wenya
conference: 2021 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2025
bibkey: hu2025coordinating
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.07528'}]
tags: [Interpretability And Explainability, ICCV, Agentic, Evaluation, Reinforcement
    Learning, Datasets]
---
Multi-hop claim verification is inherently challenging, requiring multi-step reasoning to construct verification chains while iteratively searching for information to uncover hidden bridging facts. This process is fundamentally interleaved, as effective reasoning relies on dynamically retrieved evidence, while effective search demands reasoning to refine queries based on partial information. To achieve this, we propose Hierarchical Agent Reasoning and Information Search (HARIS), explicitly modeling the coordinated process of reasoning-driven searching and search-informed reasoning. HARIS consists of a high-level reasoning agent that focuses on constructing the main verification chain, generating factual questions when more information is needed, and a low-level search agent that iteratively retrieves more information, refining its search based on intermediate findings. This design allows each agent to specialize in its respective task, enhancing verification accuracy and interpretability. HARIS is trained using reinforcement learning with outcome-based rewards. Experimental results on the EX-FEVER and HOVER benchmarks demonstrate that HARIS achieves strong performance, greatly advancing multi-hop claim verification.