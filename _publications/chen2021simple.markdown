---
layout: publication
title: 'Hiddencut: Simple Data Augmentation For Natural Language Understanding With
  Better Generalization'
authors: Jiaao Chen, Dinghan Shen, Weizhu Chen, Diyi Yang
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
citations: 15
bibkey: chen2021simple
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.00149'}, {name: Code,
    url: 'https://github.com/GT-SALT/HiddenCut'}]
tags: [Has Code, Model Architecture, Attention Mechanism, Transformer, Fine-Tuning,
  RAG, Training Techniques, Evaluation]
---
Fine-tuning large pre-trained models with task-specific data has achieved
great success in NLP. However, it has been demonstrated that the majority of
information within the self-attention networks is redundant and not utilized
effectively during the fine-tuning stage. This leads to inferior results when
generalizing the obtained models to out-of-domain distributions. To this end,
we propose a simple yet effective data augmentation technique, HiddenCut, to
better regularize the model and encourage it to learn more generalizable
features. Specifically, contiguous spans within the hidden space are
dynamically and strategically dropped during training. Experiments show that
our HiddenCut method outperforms the state-of-the-art augmentation methods on
the GLUE benchmark, and consistently exhibits superior generalization
performances on out-of-distribution and challenging counterexamples. We have
publicly released our code at https://github.com/GT-SALT/HiddenCut.