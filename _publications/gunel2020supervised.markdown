---
layout: publication
title: Supervised Contrastive Learning For Pre-trained Language Model Fine-tuning
authors: Gunel et al.
conference: Arxiv
year: 2020
bibkey: gunel2020supervised
citations: 221
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2011.01403'}]
tags: [Training Techniques, Evaluation, BERT, Model Architecture, Few Shot, Fine Tuning,
  Datasets]
---
State-of-the-art natural language understanding classification models follow
two-stages: pre-training a large language model on an auxiliary task, and then
fine-tuning the model on a task-specific labeled dataset using cross-entropy
loss. However, the cross-entropy loss has several shortcomings that can lead to
sub-optimal generalization and instability. Driven by the intuition that good
generalization requires capturing the similarity between examples in one class
and contrasting them with examples in other classes, we propose a supervised
contrastive learning (SCL) objective for the fine-tuning stage. Combined with
cross-entropy, our proposed SCL loss obtains significant improvements over a
strong RoBERTa-Large baseline on multiple datasets of the GLUE benchmark in
few-shot learning settings, without requiring specialized architecture, data
augmentations, memory banks, or additional unsupervised data. Our proposed
fine-tuning objective leads to models that are more robust to different levels
of noise in the fine-tuning training data, and can generalize better to related
tasks with limited labeled data.