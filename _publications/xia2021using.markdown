---
layout: publication
title: Using Prior Knowledge To Guide Bert's Attention In Semantic Textual Matching
  Tasks
authors: Tingyu Xia, Yue Wang, Yuan Tian, Yi Chang
conference: Arxiv
year: 2021
citations: 25
bibkey: xia2021using
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.10934'}]
tags: [Training Techniques, Transformer, Fine-Tuning, Attention Mechanism, BERT, Model
    Architecture]
---
We study the problem of incorporating prior knowledge into a deep
Transformer-based model,i.e.,Bidirectional Encoder Representations from
Transformers (BERT), to enhance its performance on semantic textual matching
tasks. By probing and analyzing what BERT has already known when solving this
task, we obtain better understanding of what task-specific knowledge BERT needs
the most and where it is most needed. The analysis further motivates us to take
a different approach than most existing works. Instead of using prior knowledge
to create a new training task for fine-tuning BERT, we directly inject
knowledge into BERT's multi-head attention mechanism. This leads us to a simple
yet effective approach that enjoys fast training stage as it saves the model
from training on additional data or tasks other than the main task. Extensive
experiments demonstrate that the proposed knowledge-enhanced BERT is able to
consistently improve semantic textual matching performance over the original
BERT model, and the performance benefit is most salient when training data is
scarce.