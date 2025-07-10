---
layout: publication
title: 'TIME: Text And Image Mutual-translation Adversarial Networks'
authors: Bingchen Liu, Kunpeng Song, Yizhe Zhu, Gerard De Melo, Ahmed Elgammal
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
citations: 27
bibkey: liu2020text
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.13192'}]
tags: [Security, Model Architecture, Transformer, Tools, Multimodal Models, Pre-Training,
  Training Techniques]
---
Focusing on text-to-image (T2I) generation, we propose Text and Image
Mutual-Translation Adversarial Networks (TIME), a lightweight but effective
model that jointly learns a T2I generator G and an image captioning
discriminator D under the Generative Adversarial Network framework. While
previous methods tackle the T2I problem as a uni-directional task and use
pre-trained language models to enforce the image--text consistency, TIME
requires neither extra modules nor pre-training. We show that the performance
of G can be boosted substantially by training it jointly with D as a language
model. Specifically, we adopt Transformers to model the cross-modal connections
between the image features and word embeddings, and design an annealing
conditional hinge loss that dynamically balances the adversarial learning. In
our experiments, TIME achieves state-of-the-art (SOTA) performance on the CUB
and MS-COCO dataset (Inception Score of 4.91 and Fr\'echet Inception Distance
of 14.3 on CUB), and shows promising performance on MS-COCO on image captioning
and downstream vision-language tasks.