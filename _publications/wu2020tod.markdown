---
layout: publication
title: 'TOD-BERT: Pre-trained Natural Language Understanding For Task-oriented Dialogue'
authors: Wu et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: wu2020tod
citations: 188
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.06871'}]
tags: [Training Techniques, EMNLP, Masked Language Model, BERT, Model Architecture,
  Few Shot, Language Modeling, Reinforcement Learning, Applications, Datasets]
---
The underlying difference of linguistic patterns between general text and
task-oriented dialogue makes existing pre-trained language models less useful
in practice. In this work, we unify nine human-human and multi-turn
task-oriented dialogue datasets for language modeling. To better model dialogue
behavior during pre-training, we incorporate user and system tokens into the
masked language modeling. We propose a contrastive objective function to
simulate the response selection task. Our pre-trained task-oriented dialogue
BERT (TOD-BERT) outperforms strong baselines like BERT on four downstream
task-oriented dialogue applications, including intention recognition, dialogue
state tracking, dialogue act prediction, and response selection. We also show
that TOD-BERT has a stronger few-shot ability that can mitigate the data
scarcity problem for task-oriented dialogue.