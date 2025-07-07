---
layout: publication
title: Synchronous Bidirectional Inference For Neural Sequence Generation
authors: Jiajun Zhang, Long Zhou, Yang Zhao, Chengqing Zong
conference: Arxiv
year: 2019
citations: 18
bibkey: zhang2019synchronous
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.08955'}]
tags: [Efficiency and Optimization, Attention Mechanism, Transformer, Model Architecture]
---
In sequence to sequence generation tasks (e.g. machine translation and
abstractive summarization), inference is generally performed in a left-to-right
manner to produce the result token by token. The neural approaches, such as
LSTM and self-attention networks, are now able to make full use of all the
predicted history hypotheses from left side during inference, but cannot
meanwhile access any future (right side) information and usually generate
unbalanced outputs in which left parts are much more accurate than right ones.
In this work, we propose a synchronous bidirectional inference model to
generate outputs using both left-to-right and right-to-left decoding
simultaneously and interactively. First, we introduce a novel beam search
algorithm that facilitates synchronous bidirectional decoding. Then, we present
the core approach which enables left-to-right and right-to-left decoding to
interact with each other, so as to utilize both the history and future
predictions simultaneously during inference. We apply the proposed model to
both LSTM and self-attention networks. In addition, we propose two strategies
for parameter optimization. The extensive experiments on machine translation
and abstractive summarization demonstrate that our synchronous bidirectional
inference model can achieve remarkable improvements over the strong baselines.