---
layout: publication
title: Multi-teacher Language-aware Knowledge Distillation For Multilingual Speech
  Emotion Recognition
authors: Bijoy et al.
conference: ICASSP 2022 - 2022 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2025
bibkey: bijoy2025multi
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.08717'}]
tags: [RAG, Training Techniques, Distillation, Alt, ICASSP, Efficiency And Optimization,
  Fine Tuning, Datasets]
---
Speech Emotion Recognition (SER) is crucial for improving human-computer interaction. Despite strides in monolingual SER, extending them to build a multilingual system remains challenging. Our goal is to train a single model capable of multilingual SER by distilling knowledge from multiple teacher models. To address this, we introduce a novel language-aware multi-teacher knowledge distillation method to advance SER in English, Finnish, and French. It leverages Wav2Vec2.0 as the foundation of monolingual teacher models and then distills their knowledge into a single multilingual student model. The student model demonstrates state-of-the-art performance, with a weighted recall of 72.9 on the English dataset and an unweighted recall of 63.4 on the Finnish dataset, surpassing fine-tuning and knowledge distillation baselines. Our method excels in improving recall for sad and neutral emotions, although it still faces challenges in recognizing anger and happiness.