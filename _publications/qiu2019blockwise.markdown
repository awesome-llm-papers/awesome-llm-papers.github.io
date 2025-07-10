---
layout: publication
title: Blockwise Self-attention For Long Document Understanding
authors: Jiezhong Qiu et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2019
citations: 68
bibkey: qiu2019blockwise
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.02972'}]
tags: [Model Architecture, Attention Mechanism, Transformer, RAG, Pre-Training, BERT,
  Training Techniques, Evaluation]
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