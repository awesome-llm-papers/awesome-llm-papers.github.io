---
layout: publication
title: 'Over-tokenized Transformer: Vocabulary Is Generally Worth Scaling'
authors: Hongzhi Huang, Defa Zhu, Banggu Wu, Yutao Zeng, Ya Wang, Qiyang Min, Xun
  Zhou
conference: No Venue
year: 2025
bibkey: huang2025over
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.16975'}]
tags: ["Efficiency", "Model Architecture", "Training Techniques"]
short_authors: Huang et al.
---
Tokenization is a fundamental component of large language models (LLMs), yet its influence on model scaling and performance is not fully explored. In this paper, we introduce Over-Tokenized Transformers, a novel framework that decouples input and output vocabularies to improve language modeling performance. Specifically, our approach scales up input vocabularies to leverage multi-gram tokens. Through extensive experiments, we uncover a log-linear relationship between input vocabulary size and training loss, demonstrating that larger input vocabularies consistently enhance model performance, regardless of model size. Using a large input vocabulary, we achieve performance comparable to double-sized baselines with no additional cost. Our findings highlight the importance of tokenization in scaling laws and provide practical insight for tokenizer design, paving the way for more efficient and powerful LLMs.

https://huggingface.co/discussions/paper/6799b346a66ae6b357bef9e3