---
layout: publication
title: A Generative Language Model For Few-shot Aspect-based Sentiment Analysis
authors: Ehsan Hosseini-asl, Wenhao Liu, Caiming Xiong
conference: Arxiv
year: 2022
citations: 15
bibkey: hosseiniasl2022generative
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.05356'}]
tags: [Training Techniques, GPT, RAG, Few-Shot, Attention Mechanism, BERT, Security,
  Model Architecture]
---
Sentiment analysis is an important task in natural language processing. In
recent works, pre-trained language models are often used to achieve
state-of-the-art results, especially when training data is scarce. It is common
to fine-tune on the downstream task, usually by adding task-specific layers on
top of the model. In this paper, we focus on aspect-based sentiment analysis,
which involves extracting aspect term, category, and predicting their
corresponding polarities. In particular, we are interested in few-shot
settings. We propose to reformulate the extraction and prediction tasks into
the sequence generation task, using a generative language model with
unidirectional attention (GPT2 is used unless stated otherwise). This way, the
model learns to accomplish the tasks via language generation without the need
of training task-specific layers. Our evaluation results on the single-task
polarity prediction show that our approach outperforms the previous
state-of-the-art (based on BERT) on average performance by a large margins in
few-shot and full-shot settings. More importantly, our generative approach
significantly reduces the model variance caused by low-resource data. We
further demonstrate that the proposed generative language model can handle
joint and multi-task settings, unlike previous work. We observe that the
proposed sequence generation method achieves further improved performances on
polarity prediction when the model is trained via joint and multi-task
settings. Further evaluation on similar sentiment analysis datasets, SST-2,
SST- and OOS intent detection validates the superiority and noise robustness of
generative language model in few-shot settings.