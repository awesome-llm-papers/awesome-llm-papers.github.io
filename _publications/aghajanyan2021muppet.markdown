---
layout: publication
title: 'Muppet: Massive Multi-task Representations With Pre-finetuning'
authors: Aghajanyan et al.
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
bibkey: aghajanyan2021muppet
citations: 163
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2101.11038'}]
tags: [RAG, EMNLP, Training Techniques, BERT, Model Architecture, Efficiency And Optimization,
  Reinforcement Learning, Fine Tuning, Datasets]
---
We propose pre-finetuning, an additional large-scale learning stage between
language model pre-training and fine-tuning. Pre-finetuning is massively
multi-task learning (around 50 datasets, over 4.8 million total labeled
examples), and is designed to encourage learning of representations that
generalize better to many different tasks. We show that pre-finetuning
consistently improves performance for pretrained discriminators (e.g.~RoBERTa)
and generation models (e.g.~BART) on a wide range of tasks (sentence
prediction, commonsense reasoning, MRC, etc.), while also significantly
improving sample efficiency during fine-tuning. We also show that large-scale
multi-tasking is crucial; pre-finetuning can hurt performance when few tasks
are used up until a critical point (usually above 15) after which performance
improves linearly in the number of tasks.