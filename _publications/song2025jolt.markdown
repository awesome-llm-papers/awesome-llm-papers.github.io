---
layout: publication
title: 'JOLT-SQL: Joint Loss Tuning Of Text-to-sql With Confusion-aware Noisy Schema
  Sampling'
authors: Song et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2025
bibkey: song2025jolt
citations: 176
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.14305'}]
tags: [Security, Model Architecture, Prompting, Tools, Training Techniques, Efficiency
    And Optimization, Fine Tuning, Evaluation, Merging, ACL, Datasets, Attention Mechanism]
---
Text-to-SQL, which maps natural language to SQL queries, has benefited greatly from recent advances in Large Language Models (LLMs). While LLMs offer various paradigms for this task, including prompting and supervised fine-tuning (SFT), SFT approaches still face challenges such as complex multi-stage pipelines and poor robustness to noisy schema information. To address these limitations, we present JOLT-SQL, a streamlined single-stage SFT framework that jointly optimizes schema linking and SQL generation via a unified loss. JOLT-SQL employs discriminative schema linking, enhanced by local bidirectional attention, alongside a confusion-aware noisy schema sampling strategy with selective attention to improve robustness under noisy schema conditions. Experiments on the Spider and BIRD benchmarks demonstrate that JOLT-SQL achieves state-of-the-art execution accuracy among comparable-size open-source models, while significantly improving both training and inference efficiency.