---
layout: publication
title: Model Compression With Multi-task Knowledge Distillation For Web-scale Question
  Answering System
authors: Yang et al.
conference: Proceedings of the 13th International Conference on Web Search and Data
  Mining
year: 2019
bibkey: yang2019model
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.09636'}]
tags: [RAG, Training Techniques, Distillation, GPT, BERT, Model Architecture, Efficiency
    And Optimization, Fine Tuning, Quantization]
---
Deep pre-training and fine-tuning models (like BERT, OpenAI GPT) have
demonstrated excellent results in question answering areas. However, due to the
sheer amount of model parameters, the inference speed of these models is very
slow. How to apply these complex models to real business scenarios becomes a
challenging but practical problem. Previous works often leverage model
compression approaches to resolve this problem. However, these methods usually
induce information loss during the model compression procedure, leading to
incomparable results between compressed model and the original model. To tackle
this challenge, we propose a Multi-task Knowledge Distillation Model (MKDM for
short) for web-scale Question Answering system, by distilling knowledge from
multiple teacher models to a light-weight student model. In this way, more
generalized knowledge can be transferred. The experiment results show that our
method can significantly outperform the baseline methods and even achieve
comparable results with the original teacher models, along with significant
speedup of model inference.