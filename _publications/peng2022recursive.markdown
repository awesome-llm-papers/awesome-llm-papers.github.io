---
layout: publication
title: Recursive Attentive Methods With Reused Item Representations For Sequential
  Recommendation
authors: Peng Bo, Parthasarathy Srinivasan, Ning Xia
conference: Proceedings of The Web Conference 2020
year: 2022
bibkey: peng2022recursive
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2209.07997'}]
tags: [Attention Mechanism, Evaluation, Transformer, Model Architecture, Datasets]
---
Sequential recommendation aims to recommend the next item of users' interest
based on their historical interactions. Recently, the self-attention mechanism
has been adapted for sequential recommendation, and demonstrated
state-of-the-art performance. However, in this manuscript, we show that the
self-attention-based sequential recommendation methods could suffer from the
localization-deficit issue. As a consequence, in these methods, over the first
few blocks, the item representations may quickly diverge from their original
representations, and thus, impairs the learning in the following blocks. To
mitigate this issue, in this manuscript, we develop a recursive attentive
method with reused item representations (RAM) for sequential recommendation. We
compare RAM with five state-of-the-art baseline methods on six public benchmark
datasets. Our experimental results demonstrate that RAM significantly
outperforms the baseline methods on benchmark datasets, with an improvement of
as much as 11.3%. Our stability analysis shows that RAM could enable deeper and
wider models for better performance. Our run-time performance comparison
signifies that RAM could also be more efficient on benchmark datasets.