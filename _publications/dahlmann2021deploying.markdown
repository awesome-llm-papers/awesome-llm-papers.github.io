---
layout: publication
title: 'Deploying A Bert-based Query-title Relevance Classifier In A Production System:
  A View From The Trenches'
authors: Dahlmann Leonard, Lancewicki Tomer
conference: Proceedings of the 42nd International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2021
bibkey: dahlmann2021deploying
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2108.10197'}]
tags: [Distillation, BERT, Transformer, Model Architecture, Efficiency And Optimization,
  Reinforcement Learning, SIGIR, Applications, Datasets]
---
The Bidirectional Encoder Representations from Transformers (BERT) model has
been radically improving the performance of many Natural Language Processing
(NLP) tasks such as Text Classification and Named Entity Recognition (NER)
applications. However, it is challenging to scale BERT for low-latency and
high-throughput industrial use cases due to its enormous size. We successfully
optimize a Query-Title Relevance (QTR) classifier for deployment via a compact
model, which we name BERT Bidirectional Long Short-Term Memory (BertBiLSTM).
The model is capable of inferring an input in at most 0.2ms on CPU. BertBiLSTM
exceeds the off-the-shelf BERT model's performance in terms of accuracy and
efficiency for the aforementioned real-world production task. We achieve this
result in two phases. First, we create a pre-trained model, called eBERT, which
is the original BERT architecture trained with our unique item title corpus. We
then fine-tune eBERT for the QTR task. Second, we train the BertBiLSTM model to
mimic the eBERT model's performance through a process called Knowledge
Distillation (KD) and show the effect of data augmentation to achieve the
resembling goal. Experimental results show that the proposed model outperforms
other compact and production-ready models.