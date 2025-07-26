---
layout: publication
title: Integrating Multimodal Information In Large Pretrained Transformers
authors: Wasifur Rahman, Md. Kamrul Hasan, Sangwu Lee, Amir Zadeh, Chengfeng Mao,
  Louis-philippe Morency, Ehsan Hoque
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: rahman2019integrating
citations: 409
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.05787'}]
tags: ["Applications", "Datasets", "Fine-Tuning", "Model Architecture", "Training Techniques"]
short_authors: Rahman et al.
---
Recent Transformer-based contextual word representations, including BERT and
XLNet, have shown state-of-the-art performance in multiple disciplines within
NLP. Fine-tuning the trained contextual models on task-specific datasets has
been the key to achieving superior performance downstream. While fine-tuning
these pre-trained models is straightforward for lexical applications
(applications with only language modality), it is not trivial for multimodal
language (a growing area in NLP focused on modeling face-to-face
communication). Pre-trained models don't have the necessary components to
accept two extra modalities of vision and acoustic. In this paper, we proposed
an attachment to BERT and XLNet called Multimodal Adaptation Gate (MAG). MAG
allows BERT and XLNet to accept multimodal nonverbal data during fine-tuning.
It does so by generating a shift to internal representation of BERT and XLNet;
a shift that is conditioned on the visual and acoustic modalities. In our
experiments, we study the commonly used CMU-MOSI and CMU-MOSEI datasets for
multimodal sentiment analysis. Fine-tuning MAG-BERT and MAG-XLNet significantly
boosts the sentiment analysis performance over previous baselines as well as
language-only fine-tuning of BERT and XLNet. On the CMU-MOSI dataset, MAG-XLNet
achieves human-level multimodal sentiment analysis performance for the first
time in the NLP community.