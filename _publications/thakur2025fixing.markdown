---
layout: publication
title: 'Fixing Data That Hurts Performance: Cascading Llms To Relabel Hard Negatives
  For Robust Information Retrieval'
authors: Thakur et al.
conference: Proceedings of the 44th International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2025
bibkey: thakur2025fixing
citations: 127
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.16967'}]
tags: [Training Techniques, GPT, Prompting, Evaluation, Model Architecture, Efficiency
    And Optimization, Reinforcement Learning, SIGIR, Pruning, Datasets]
---
Training robust retrieval and reranker models typically relies on large-scale retrieval datasets; for example, the BGE collection contains 1.6 million query-passage pairs sourced from various data sources. However, we find that certain datasets can negatively impact model effectiveness -- pruning 8 out of 15 datasets from the BGE collection reduces the training set size by 2.35\\(\times\\) and increases nDCG@10 on BEIR by 1.0 point. This motivates a deeper examination of training data quality, with a particular focus on "false negatives", where relevant passages are incorrectly labeled as irrelevant. We propose a simple, cost-effective approach using cascading LLM prompts to identify and relabel hard negatives. Experimental results show that relabeling false negatives with true positives improves both E5 (base) and Qwen2.5-7B retrieval models by 0.7-1.4 nDCG@10 on BEIR and by 1.7-1.8 nDCG@10 on zero-shot AIR-Bench evaluation. Similar gains are observed for rerankers fine-tuned on the relabeled data, such as Qwen2.5-3B on BEIR. The reliability of the cascading design is further supported by human annotation results, where we find judgment by GPT-4o shows much higher agreement with humans than GPT-4o-mini.