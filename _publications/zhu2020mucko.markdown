---
layout: publication
title: 'Mucko: Multi-layer Cross-modal Knowledge Reasoning For Fact-based Visual Question
  Answering'
authors: Zihao Zhu, Jing Yu, Yujing Wang, Yajing Sun, Yue Hu, Qi Wu
conference: Proceedings of the Twenty-Ninth International Joint Conference on Artificial
  Intelligence
year: 2020
bibkey: zhu2020mucko
citations: 103
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.09073'}]
tags: ["IJCAI"]
short_authors: Zhu et al.
---
Fact-based Visual Question Answering (FVQA) requires external knowledge
beyond visible content to answer questions about an image, which is challenging
but indispensable to achieve general VQA. One limitation of existing FVQA
solutions is that they jointly embed all kinds of information without
fine-grained selection, which introduces unexpected noises for reasoning the
final answer. How to capture the question-oriented and
information-complementary evidence remains a key challenge to solve the
problem. In this paper, we depict an image by a multi-modal heterogeneous
graph, which contains multiple layers of information corresponding to the
visual, semantic and factual features. On top of the multi-layer graph
representations, we propose a modality-aware heterogeneous graph convolutional
network to capture evidence from different layers that is most relevant to the
given question. Specifically, the intra-modal graph convolution selects
evidence from each modality and cross-modal graph convolution aggregates
relevant information across different modalities. By stacking this process
multiple times, our model performs iterative reasoning and predicts the optimal
answer by analyzing all question-oriented evidence. We achieve a new
state-of-the-art performance on the FVQA task and demonstrate the effectiveness
and interpretability of our model with extensive experiments.