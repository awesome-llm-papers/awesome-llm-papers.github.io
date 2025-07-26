---
layout: publication
title: BERT With History Answer Embedding For Conversational Question Answering
authors: Chen Qu, Liu Yang, Minghui Qiu, W. Bruce Croft, Yongfeng Zhang, Mohit Iyyer
conference: Proceedings of the 42nd International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2019
bibkey: qu2019bert
citations: 206
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.05412'}]
tags: ["Model Architecture", "SIGIR"]
short_authors: Qu et al.
---
Conversational search is an emerging topic in the information retrieval
community. One of the major challenges to multi-turn conversational search is
to model the conversation history to answer the current question. Existing
methods either prepend history turns to the current question or use complicated
attention mechanisms to model the history. We propose a conceptually simple yet
highly effective approach referred to as history answer embedding. It enables
seamless integration of conversation history into a conversational question
answering (ConvQA) model built on BERT (Bidirectional Encoder Representations
from Transformers). We first explain our view that ConvQA is a simplified but
concrete setting of conversational search, and then we provide a general
framework to solve ConvQA. We further demonstrate the effectiveness of our
approach under this framework. Finally, we analyze the impact of different
numbers of history turns under different settings to provide new insights into
conversation history modeling in ConvQA.