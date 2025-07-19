---
layout: publication
title: Dual Decomposition Of Weights And Singular Value Low Rank Adaptation
authors: Han Jialong, Zhang Si, Zhang Ke
conference: Physical Review A
year: 2025
bibkey: han2025dual
citations: 98
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.14367'}]
tags: [Training Techniques, Evaluation, Efficiency And Optimization, Reinforcement
    Learning, Security, Fine Tuning]
---
Parameter-Efficient Fine-Tuning (PEFT) has emerged as a critical paradigm for adapting Large Language Models (LLMs) to downstream tasks, among which Low-rank Adaptation (LoRA) represents one of the most widely adopted methodologies. However, existing LoRA-based approaches exhibit two fundamental limitations: unstable training dynamics and inefficient knowledge transfer from pre-trained models, both stemming from random initialization of adapter parameters. To overcome these challenges, we propose DuDe, a novel approach that decomposes weight matrices into magnitude and direction components, employing Singular Value Decomposition (SVD) for principled initialization. Our comprehensive evaluation demonstrates DuDe's superior performance and robustness, achieving up to 48.35% accuracy on MMLU and 62.53% (\\(\pm\\) 1.59) accuracy on GSM8K. Our theoretical analysis and empirical validation collectively demonstrate that DuDe's decomposition strategy enhances optimization stability and better preserves pre-trained representations, particularly for domain-specific tasks requiring specialized knowledge. The combination of robust empirical performance and rigorous theoretical foundations establishes DuDe as a significant contribution to PEFT methodologies for LLMs.