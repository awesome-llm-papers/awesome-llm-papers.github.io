---
layout: publication
title: A Reinforced Topic-aware Convolutional Sequence-to-sequence Model For Abstractive
  Text Summarization
authors: Wang et al.
conference: Proceedings of the Twenty-Seventh International Joint Conference on Artificial
  Intelligence
year: 2018
bibkey: wang2018reinforced
citations: 126
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.03616'}]
tags: [Ethics And Bias, Training Techniques, Efficiency And Optimization, Evaluation,
  AAAI, IJCAI, Datasets]
---
In this paper, we propose a deep learning approach to tackle the automatic
summarization tasks by incorporating topic information into the convolutional
sequence-to-sequence (ConvS2S) model and using self-critical sequence training
(SCST) for optimization. Through jointly attending to topics and word-level
alignment, our approach can improve coherence, diversity, and informativeness
of generated summaries via a biased probability generation mechanism. On the
other hand, reinforcement training, like SCST, directly optimizes the proposed
model with respect to the non-differentiable metric ROUGE, which also avoids
the exposure bias during inference. We carry out the experimental evaluation
with state-of-the-art methods over the Gigaword, DUC-2004, and LCSTS datasets.
The empirical results demonstrate the superiority of our proposed method in the
abstractive summarization.