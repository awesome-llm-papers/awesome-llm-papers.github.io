---
layout: publication
title: 'Intermediate-task Transfer Learning With Pretrained Models For Natural Language
  Understanding: When And Why Does It Work?'
authors: Pruksachatkun et al.
conference: Arxiv
year: 2020
bibkey: pruksachatkun2020intermediate
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.00628'}]
tags: [RAG, Training Techniques, Evaluation, BERT, Model Architecture, Reinforcement
    Learning, Fine Tuning, Datasets]
---
While pretrained models such as BERT have shown large gains across natural
language understanding tasks, their performance can be improved by further
training the model on a data-rich intermediate task, before fine-tuning it on a
target task. However, it is still poorly understood when and why
intermediate-task training is beneficial for a given target task. To
investigate this, we perform a large-scale study on the pretrained RoBERTa
model with 110 intermediate-target task combinations. We further evaluate all
trained models with 25 probing tasks meant to reveal the specific skills that
drive transfer. We observe that intermediate tasks requiring high-level
inference and reasoning abilities tend to work best. We also observe that
target task performance is strongly correlated with higher-level abilities such
as coreference resolution. However, we fail to observe more granular
correlations between probing and target task performance, highlighting the need
for further work on broad-coverage probing benchmarks. We also observe evidence
that the forgetting of knowledge learned during pretraining may limit our
analysis, highlighting the need for further work on transfer learning methods
in these settings.