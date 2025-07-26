---
layout: publication
title: Neural Paraphrase Generation With Stacked Residual LSTM Networks
authors: Aaditya Prakash, Sadid A. Hasan, Kathy Lee, Vivek Datla, Ashequl Qadir, Joey
  Liu, Oladimeji Farri
conference: Arxiv
year: 2016
bibkey: prakash2016neural
citations: 229
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1610.03098'}]
tags: ["Model Architecture"]
short_authors: Prakash et al.
---
In this paper, we propose a novel neural approach for paraphrase generation.
Conventional para- phrase generation methods either leverage hand-written rules
and thesauri-based alignments, or use statistical machine learning principles.
To the best of our knowledge, this work is the first to explore deep learning
models for paraphrase generation. Our primary contribution is a stacked
residual LSTM network, where we add residual connections between LSTM layers.
This allows for efficient training of deep LSTMs. We evaluate our model and
other state-of-the-art deep learning models on three different datasets: PPDB,
WikiAnswers and MSCOCO. Evaluation results demonstrate that our model
outperforms sequence to sequence, attention-based and bi- directional LSTM
models on BLEU, METEOR, TER and an embedding-based sentence similarity metric.