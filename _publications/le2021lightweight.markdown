---
layout: publication
title: Lightweight Adapter Tuning For Multilingual Speech Translation
authors: Le et al.
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 2: Short Papers)'
year: 2021
bibkey: le2021lightweight
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.01463'}]
tags: [ACL, Training Techniques, Fine Tuning, Alt]
---
Adapter modules were recently introduced as an efficient alternative to
fine-tuning in NLP. Adapter tuning consists in freezing pretrained parameters
of a model and injecting lightweight modules between layers, resulting in the
addition of only a small number of task-specific trainable parameters. While
adapter tuning was investigated for multilingual neural machine translation,
this paper proposes a comprehensive analysis of adapters for multilingual
speech translation (ST). Starting from different pre-trained models (a
multilingual ST trained on parallel data or a multilingual BART (mBART) trained
on non-parallel multilingual data), we show that adapters can be used to: (a)
efficiently specialize ST to specific language pairs with a low extra cost in
terms of parameters, and (b) transfer from an automatic speech recognition
(ASR) task and an mBART pre-trained model to a multilingual ST task.
Experiments show that adapter tuning offer competitive results to full
fine-tuning, while being much more parameter-efficient.