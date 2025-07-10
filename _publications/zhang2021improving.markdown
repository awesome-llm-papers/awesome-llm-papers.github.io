---
layout: publication
title: Improving Stack Overflow Question Title Generation With Copying Enhanced Codebert
  Model And Bi-modal Information
authors: Fengji Zhang et al.
conference: Information and Software Technology
year: 2021
citations: 23
bibkey: zhang2021improving
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.13073'}]
tags: [Model Architecture, Attention Mechanism, Transformer, BERT, Evaluation]
---
Context: Stack Overflow is very helpful for software developers who are
seeking answers to programming problems. Previous studies have shown that a
growing number of questions are of low quality and thus obtain less attention
from potential answerers. Gao et al. proposed an LSTM-based model (i.e.,
BiLSTM-CC) to automatically generate question titles from the code snippets to
improve the question quality. However, only using the code snippets in the
question body cannot provide sufficient information for title generation, and
LSTMs cannot capture the long-range dependencies between tokens. Objective:
This paper proposes CCBERT, a deep learning based novel model to enhance the
performance of question title generation by making full use of the bi-modal
information of the entire question body. Method: CCBERT follows the
encoder-decoder paradigm and uses CodeBERT to encode the question body into
hidden representations, a stacked Transformer decoder to generate predicted
tokens, and an additional copy attention layer to refine the output
distribution. Both the encoder and decoder perform the multi-head
self-attention operation to better capture the long-range dependencies. This
paper builds a dataset containing around 200,000 high-quality questions
filtered from the data officially published by Stack Overflow to verify the
effectiveness of the CCBERT model. Results: CCBERT outperforms all the baseline
models on the dataset. Experiments on both code-only and low-resource datasets
show the superiority of CCBERT with less performance degradation. The human
evaluation also shows the excellent performance of CCBERT concerning both
readability and correlation criteria.