---
layout: publication
title: 'Make Lora Great Again: Boosting Lora With Adaptive Singular Values And Mixture-of-experts
  Optimization Alignment'
authors: Chenghao Fan, Zhenyi Lu, Sichen Liu, Xiaoye Qu, Wei Wei, Chengfeng Gu, Yu
  Cheng
conference: No Venue
year: 2025
bibkey: fan2025make
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.16894'}]
tags: ["Efficiency", "Fine-Tuning", "Model Architecture", "Training Techniques"]
short_authors: Fan et al.
---
While Low-Rank Adaptation (LoRA) enables parameter-efficient fine-tuning for Large Language Models (LLMs), its performance often falls short of Full Fine-Tuning (Full FT). Current methods optimize LoRA by initializing with static singular value decomposition (SVD) subsets, leading to suboptimal leveraging of pre-trained knowledge. Another path for improving LoRA is incorporating a Mixture-of-Experts (MoE) architecture. However, weight misalignment and complex gradient dynamics make it challenging to adopt SVD prior to the LoRA MoE architecture. To mitigate these issues, we propose Great LoRA Mixture-of-Expert (GOAT), a framework that (1) adaptively integrates relevant priors using an SVD-structured MoE, and (2) aligns optimization with full fine-tuned MoE by deriving a theoretical scaling factor. We demonstrate that proper scaling, without modifying the architecture or training algorithms, boosts LoRA MoE's efficiency and performance. Experiments across 25 datasets, including natural language understanding, commonsense reasoning, image classification, and natural language generation, demonstrate GOAT's state-of-the-art performance, closing the gap with Full FT.

https://huggingface.co/discussions/paper/67bd396fa06bae99f3866964