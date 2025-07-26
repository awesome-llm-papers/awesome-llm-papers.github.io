---
layout: publication
title: Blockwise Self-attention For Long Document Understanding
authors: Jiezhong Qiu, Hao Ma, Omer Levy, Scott Wen-tau Yih, Sinong Wang, Jie Tang
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: qiu2019blockwise
citations: 142
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.02972'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Qiu et al.
---
We present BlockBERT, a lightweight and efficient BERT model for better
modeling long-distance dependencies. Our model extends BERT by introducing
sparse block structures into the attention matrix to reduce both memory
consumption and training/inference time, which also enables attention heads to
capture either short- or long-range contextual information. We conduct
experiments on language model pre-training and several benchmark question
answering datasets with various paragraph lengths. BlockBERT uses 18.7-36.1%
less memory and 12.0-25.1% less time to learn the model. During testing,
BlockBERT saves 27.8% inference time, while having comparable and sometimes
better prediction accuracy, compared to an advanced BERT-based model, RoBERTa.