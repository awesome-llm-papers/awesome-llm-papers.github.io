---
layout: publication
title: 'TRANS-BLSTM: Transformer With Bidirectional LSTM For Language Understanding'
authors: Zhiheng Huang, Peng Xu, Davis Liang, Ajay Mishra, Bing Xiang
conference: Arxiv
year: 2020
citations: 23
bibkey: huang2020trans
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2003.07000'}]
tags: [Transformer, Tools, BERT, Model Architecture]
---
Bidirectional Encoder Representations from Transformers (BERT) has recently
achieved state-of-the-art performance on a broad range of NLP tasks including
sentence classification, machine translation, and question answering. The BERT
model architecture is derived primarily from the transformer. Prior to the
transformer era, bidirectional Long Short-Term Memory (BLSTM) has been the
dominant modeling architecture for neural machine translation and question
answering. In this paper, we investigate how these two modeling techniques can
be combined to create a more powerful model architecture. We propose a new
architecture denoted as Transformer with BLSTM (TRANS-BLSTM) which has a BLSTM
layer integrated to each transformer block, leading to a joint modeling
framework for transformer and BLSTM. We show that TRANS-BLSTM models
consistently lead to improvements in accuracy compared to BERT baselines in
GLUE and SQuAD 1.1 experiments. Our TRANS-BLSTM model obtains an F1 score of
94.01% on the SQuAD 1.1 development dataset, which is comparable to the
state-of-the-art result.