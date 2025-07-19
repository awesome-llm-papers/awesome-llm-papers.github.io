---
layout: publication
title: Optimizing Non-autoregressive Transformers With Contrastive Learning
authors: An et al.
conference: 2021 IEEE/CVF International Conference on Computer Vision Workshops (ICCVW)
year: 2023
bibkey: an2023optimizing
citations: 55
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.13667'}]
tags: [ICCV, Training Techniques, GPT, Evaluation, Transformer, Model Architecture,
  Applications, Datasets]
---
Non-autoregressive Transformers (NATs) reduce the inference latency of
Autoregressive Transformers (ATs) by predicting words all at once rather than
in sequential order. They have achieved remarkable progress in machine
translation as well as many other applications. However, a long-standing
challenge for NATs is the learning of multi-modality data distribution, which
is the main cause of the performance gap between NATs and ATs. In this paper,
we propose to ease the difficulty of modality learning via sampling from the
model distribution instead of the data distribution. We derive contrastive
constraints to stabilize the training process and integrate this resulting
objective with the state-of-the-art NAT architecture DA-Transformer. Our model
\method is examined on 3 different tasks, including machine translation, text
summarization, and paraphrasing with 5 benchmarks. Results show that our
approach outperforms previous non-autoregressive baselines by a significant
margin and establishes new state-of-the-art results for non-autoregressive
transformers on all the benchmarks.