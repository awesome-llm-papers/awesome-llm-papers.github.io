---
layout: publication
title: 'Moa: Heterogeneous Mixture Of Adapters For Parameter-efficient Fine-tuning
  Of Large Language Models'
authors: Cao et al.
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2025
bibkey: cao2025moa
citations: 86
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.05928'}]
tags: [RAG, EMNLP, Training Techniques, Model Architecture, Efficiency And Optimization,
  Reinforcement Learning, Applications, Fine Tuning, Merging]
---
Recent studies integrate Low-Rank Adaptation (LoRA) and Mixture-of-Experts (MoE) to further enhance the performance of parameter-efficient fine-tuning (PEFT) methods in Large Language Model (LLM) applications. Existing methods employ *homogeneous* MoE-LoRA architectures composed of LoRA experts with either similar or identical structures and capacities. However, these approaches often suffer from representation collapse and expert load imbalance, which negatively impact the potential of LLMs. To address these challenges, we propose a *heterogeneous* \textbf\{Mixture-of-Adapters (MoA)\} approach. This method dynamically integrates PEFT adapter experts with diverse structures, leveraging their complementary representational capabilities to foster expert specialization, thereby enhancing the effective transfer of pre-trained knowledge to downstream tasks. MoA supports two variants: \textbf\{(i)\} \textit\{Soft MoA\} achieves fine-grained integration by performing a weighted fusion of all expert outputs; \textbf\{(ii)\} \textit\{Sparse MoA\} activates adapter experts sparsely based on their contribution, achieving this with negligible performance degradation. Experimental results demonstrate that heterogeneous MoA outperforms homogeneous MoE-LoRA methods in both performance and parameter efficiency. Our project is available at https://github.com/DCDmllm/MoA.