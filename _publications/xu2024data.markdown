---
layout: publication
title: Data Efficient Evaluation Of Large Language Models And Text-to-image Models
  Via Adaptive Sampling
authors: Xu et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2023'
year: 2024
bibkey: xu2024data
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.15527'}]
tags: [Model Architecture, Tools, Evaluation, ACL, EMNLP, RAG, GPT, Datasets, Reinforcement
    Learning]
---
Evaluating LLMs and text-to-image models is a computationally intensive task
often overlooked. Efficient evaluation is crucial for understanding the diverse
capabilities of these models and enabling comparisons across a growing number
of new models and benchmarks. To address this, we introduce SubLIME, a
data-efficient evaluation framework that employs adaptive sampling techniques,
such as clustering and quality-based methods, to create representative subsets
of benchmarks. Our approach ensures statistically aligned model rankings
compared to full datasets, evidenced by high Pearson correlation coefficients.
Empirical analysis across six NLP benchmarks reveals that: (1) quality-based
sampling consistently achieves strong correlations (0.85 to 0.95) with full
datasets at a 10% sampling rate such as Quality SE and Quality CPD (2)
clustering methods excel in specific benchmarks such as MMLU (3) no single
method universally outperforms others across all metrics. Extending this
framework, we leverage the HEIM leaderboard to cover 25 text-to-image models on
17 different benchmarks. SubLIME dynamically selects the optimal technique for
each benchmark, significantly reducing evaluation costs while preserving
ranking integrity and score distribution. Notably, a minimal sampling rate of
1% proves effective for benchmarks like MMLU. Additionally, we demonstrate that
employing difficulty-based sampling to target more challenging benchmark
segments enhances model differentiation with broader score distributions. We
also combine semantic search, tool use, and GPT-4 review to identify redundancy
across benchmarks within specific LLM categories, such as coding benchmarks.
This allows us to further reduce the number of samples needed to maintain
targeted rank preservation. Overall, SubLIME offers a versatile and
cost-effective solution for the robust evaluation of LLMs and text-to-image
models.