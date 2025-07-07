---
layout: publication
title: A Comparative Study Of Transformer-based Language Models On Extractive Question
  Answering
authors: Kate Pearce, Tiffany Zhan, Aneesh Komanduri, Justin Zhan
conference: Arxiv
year: 2021
citations: 20
bibkey: pearce2021comparative
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.03142'}]
tags: [Transformer, Model Architecture, BERT]
---
Question Answering (QA) is a task in natural language processing that has
seen considerable growth after the advent of transformers. There has been a
surge in QA datasets that have been proposed to challenge natural language
processing models to improve human and existing model performance. Many
pre-trained language models have proven to be incredibly effective at the task
of extractive question answering. However, generalizability remains as a
challenge for the majority of these models. That is, some datasets require
models to reason more than others. In this paper, we train various pre-trained
language models and fine-tune them on multiple question answering datasets of
varying levels of difficulty to determine which of the models are capable of
generalizing the most comprehensively across different datasets. Further, we
propose a new architecture, BERT-BiLSTM, and compare it with other language
models to determine if adding more bidirectionality can improve model
performance. Using the F1-score as our metric, we find that the RoBERTa and
BART pre-trained models perform the best across all datasets and that our
BERT-BiLSTM model outperforms the baseline BERT model.