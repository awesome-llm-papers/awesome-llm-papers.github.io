---
layout: publication
title: 'LLM-BIP: Structured Pruning For Large Language Models With Block-wise Forward
  Importance Propagation'
authors: Wu Haihang
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2024
bibkey: wu2024llm
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.06419'}]
tags: [RAG, EMNLP, Attention Mechanism, Evaluation, Transformer, Model Architecture,
  Efficiency And Optimization, Pruning, Datasets]
---
Large language models (LLMs) have demonstrated remarkable performance across
various language tasks, but their widespread deployment is impeded by their
large size and high computational costs. Structural pruning is a prevailing
technique used to introduce sparsity into pre-trained models and facilitate
direct hardware acceleration during inference by removing redundant connections
(structurally-grouped parameters), such as channels and attention heads.
Existing structural pruning approaches often employ either global or layer-wise
pruning criteria; however, they are hindered by ineffectiveness stemming from
inaccurate evaluation of connection importance. Global pruning methods
typically assess component importance using near-zero and unreliable gradients,
while layer-wise pruning approaches encounter significant pruning error
accumulation issues. To this end, we propose a more accurate pruning metric
based on the block-wise importance score propagation, termed LLM-BIP.
Specifically, LLM-BIP precisely evaluates connection importance by gauging its
influence on the respective transformer block output, which can be efficiently
approximated in a single forward pass through an upper bound derived from the
assumption of Lipschitz continuity. We evaluate the proposed method using
LLaMA-7B, Vicuna-7B, and LLaMA-13B across common zero-shot tasks. The results
demonstrate that our approach achieves an average of 3.26% increase in accuracy
for common reasoning tasks compared to previous best baselines. It also reduces
perplexity by 14.09 and 68.76 on average for the WikiText2 dataset and PTB
dataset, respectively.