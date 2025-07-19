---
layout: publication
title: 'FASP: Fast And Accurate Structured Pruning Of Large Language Models'
authors: Hu et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2025
bibkey: hu2025fasp
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.09412'}]
tags: [EMNLP, Tools, Efficiency And Optimization, Reinforcement Learning, Quantization,
  Pruning]
---
The rapid increase in the size of large language models (LLMs) has
significantly escalated their computational and memory demands, posing
challenges for efficient deployment, especially on resource-constrained
devices. Structured pruning has emerged as an effective model compression
method that can reduce these demands while preserving performance. In this
paper, we introduce FASP (Fast and Accurate Structured Pruning), a novel
structured pruning framework for LLMs that emphasizes both speed and accuracy.
FASP employs a distinctive pruning structure that interlinks sequential layers,
allowing for the removal of columns in one layer while simultaneously
eliminating corresponding rows in the preceding layer without incurring
additional performance loss. The pruning metric, inspired by Wanda, is
computationally efficient and effectively selects components to prune.
Additionally, we propose a restoration mechanism that enhances model fidelity
by adjusting the remaining weights post-pruning. We evaluate FASP on the OPT
and LLaMA model families, demonstrating superior performance in terms of
perplexity and accuracy on downstream tasks compared to state-of-the-art
methods. Our approach achieves significant speed-ups, pruning models such as
OPT-125M in 17 seconds and LLaMA-30B in 15 minutes on a single NVIDIA RTX 4090
GPU, making it a highly practical solution for optimizing LLMs.