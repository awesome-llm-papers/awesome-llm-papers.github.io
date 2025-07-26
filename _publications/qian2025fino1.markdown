---
layout: publication
title: 'Fino1: On The Transferability Of Reasoning Enhanced Llms To Finance'
authors: Lingfei Qian, Weipeng Zhou, Yan Wang, Xueqing Peng, Jimin Huang, Qianqian
  Xie
conference: No Venue
year: 2025
bibkey: qian2025fino1
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67ad5ca59109885ce9b85a5b'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.08127'}]
tags: ["Datasets", "Evaluation", "Fine-Tuning", "Prompting", "Reinforcement Learning"]
short_authors: Qian et al.
---
Recent advancements in large language models (LLMs) have shown strong general reasoning abilities, yet their effectiveness in financial reasoning remains underexplored. In this study, we comprehensively evaluate 16 powerful reasoning and general LLMs on three complex financial tasks involving financial text, tabular data, and equations, assessing numerical reasoning, tabular interpretation, financial terminology comprehension, long-context processing, and equation-based problem solving. Our results show that while better datasets and pretraining improve financial reasoning, general enhancements like CoT fine-tuning do not always yield consistent gains. Moreover, all reasoning strategies face challenges in improving performance on long-context and multi-table tasks. To address these limitations, we develop a financial reasoning-enhanced model based on Llama-3.1-8B-Instruct, by CoT fine-tuning and reinforcement learning with domain-specific reasoning paths. Even with simple fine-tuning with one financial dataset, our model achieves a consistent 10% performance improvement across tasks, surpassing all 8B models and even Llama3-70B-Instruct and Llama3.1-70B-Instruct on average. Our results highlight the need for domain-specific adaptations in financial tasks, emphasizing future directions such as multi-table reasoning, long-context processing, and financial terminology comprehension. All our datasets, models, and codes are publicly available. Furthermore, we introduce a leaderboard for benchmarking future datasets and models.

https://huggingface.co/discussions/paper/67ad5ca59109885ce9b85a5b