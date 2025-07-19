---
layout: publication
title: 'Rankmamba: Benchmarking Mamba''s Document Ranking Performance In The Era Of
  Transformers'
authors: Xu Zhichao
conference: Proceedings of the 43rd International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2024
bibkey: xu2024rankmamba
citations: 55
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.18276'}]
tags: [Training Techniques, Attention Mechanism, Evaluation, Transformer, Model Architecture,
  Time Series, SIGIR, Datasets]
---
Transformer structure has achieved great success in multiple applied machine
learning communities, such as natural language processing (NLP), computer
vision (CV) and information retrieval (IR). Transformer architecture's core
mechanism -- attention requires \\(O(n^2)\\) time complexity in training and \\(O(n)\\)
time complexity in inference. Many works have been proposed to improve the
attention mechanism's scalability, such as Flash Attention and Multi-query
Attention. A different line of work aims to design new mechanisms to replace
attention. Recently, a notable model structure -- Mamba, which is based on
state space models, has achieved transformer-equivalent performance in multiple
sequence modeling tasks.
  In this work, we examine \mamba's efficacy through the lens of a classical IR
task -- document ranking. A reranker model takes a query and a document as
input, and predicts a scalar relevance score. This task demands the language
model's ability to comprehend lengthy contextual inputs and to capture the
interaction between query and document tokens. We find that (1) Mamba models
achieve competitive performance compared to transformer-based models with the
same training recipe; (2) but also have a lower training throughput in
comparison to efficient transformer implementations such as flash attention. We
hope this study can serve as a starting point to explore Mamba models in other
classical IR tasks. Our code implementation and trained checkpoints are made
public to facilitate reproducibility
(https://github.com/zhichaoxu-shufe/RankMamba).