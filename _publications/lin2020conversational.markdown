---
layout: publication
title: Conversational Question Reformulation Via Sequence-to-sequence Architectures
  And Pretrained Language Models
authors: Sheng-chieh Lin et al.
conference: Arxiv
year: 2020
citations: 37
bibkey: lin2020conversational
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.01909'}]
tags: [Transformer, RAG, Model Architecture, Evaluation]
---
This paper presents an empirical study of conversational question
reformulation (CQR) with sequence-to-sequence architectures and pretrained
language models (PLMs). We leverage PLMs to address the strong token-to-token
independence assumption made in the common objective, maximum likelihood
estimation, for the CQR task. In CQR benchmarks of task-oriented dialogue
systems, we evaluate fine-tuned PLMs on the recently-introduced CANARD dataset
as an in-domain task and validate the models using data from the TREC 2019 CAsT
Track as an out-domain task. Examining a variety of architectures with
different numbers of parameters, we demonstrate that the recent text-to-text
transfer transformer (T5) achieves the best results both on CANARD and CAsT
with fewer parameters, compared to similar transformer architectures.