---
layout: publication
title: How To Synthesize Text Data Without Model Collapse?
authors: Xuekai Zhu, Daixuan Cheng, Hengli Li, Kaiyan Zhang, Ermo Hua, Xingtai Lv,
  Ning Ding, Zhouhan Lin, Zilong Zheng, Bowen Zhou
conference: No Venue
year: 2024
bibkey: zhu2024how
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2412.14689'}]
tags: ["Fine-Tuning", "Model Architecture", "Training Techniques"]
short_authors: Zhu et al.
---
Model collapse in synthetic data indicates that iterative training on self-generated data leads to a gradual decline in performance. With the proliferation of AI models, synthetic data will fundamentally reshape the web data ecosystem. Future GPT-\{n\} models will inevitably be trained on a blend of synthetic and human-produced data. In this paper, we focus on two questions: what is the impact of synthetic data on language model training, and how to synthesize data without model collapse? We first pre-train language models across different proportions of synthetic data, revealing a negative correlation between the proportion of synthetic data and model performance. We further conduct statistical analysis on synthetic data to uncover distributional shift phenomenon and over-concentration of n-gram features. Inspired by the above findings, we propose token editing on human-produced data to obtain semi-synthetic data. As a proof of concept, we theoretically demonstrate that token-level editing can prevent model collapse, as the test error is constrained by a finite upper bound. We conduct extensive experiments on pre-training from scratch, continual pre-training, and supervised fine-tuning. The results validate our theoretical proof that token-level editing improves data quality and enhances model performance.

https://huggingface.co/discussions/paper/6764e1e0c51db09f8c3cd793