---
layout: publication
title: 'Compresso: Structured Pruning With Collaborative Prompting Learns Compact
  Large Language Models'
authors: Guo et al.
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2023
bibkey: guo2023compresso
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.05015'}]
tags: [Pruning, Prompting, Training Techniques, Efficiency And Optimization, Fine
    Tuning, Evaluation, Quantization, ACL, Datasets, Reinforcement Learning, Alt]
---
Despite the remarkable success of Large Language Models (LLMs), the massive
size poses significant deployment challenges, particularly on
resource-constrained hardware. While existing LLM compression methods focus on
quantization, pruning remains relatively unexplored due to the high cost of
training-based approaches and data collection challenges. One-shot pruning
methods, although cost-effective and data-free, have become dominant in LLM
pruning, but lead to performance decline under the structured pruning setting.
In this work, we introduce a new paradigm for structurally pruning LLMs, called
Compresso. Our approach, through the collaboration of the proposed
resource-efficient pruning algorithm and the LLM itself, learns optimal pruning
decisions during the training process. Compresso addresses the challenges of
expensive training costs and data collection by incorporating Low-Rank
Adaptation (LoRA) into the \\(L_0\\) regularization during the instruction tuning
process. Then, we further augment the pruning algorithm by introducing a
collaborative prompt that fosters collaboration between the LLM and the pruning
algorithm, significantly boosting the overall performance. To this end,
Compresso prunes LLaMA-7B to 5.4B, maintaining original performance and even
surpassing LLaMA-7B in reading comprehension by 2.62%. Extensive experiments
demonstrate that Compresso significantly outperforms one-shot pruning baselines
across various sparsity ratios, achieving up to 2.21%, 11.43%, 7.04%, and 4.81%
higher scores on the commonsense reasoning, reading comprehension, MMLU, and
BBH benchmarks, respectively.