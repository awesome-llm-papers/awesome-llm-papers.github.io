---
layout: publication
title: Visual Variational Autoencoder Prompt Tuning
authors: Xiao et al.
conference: Lecture Notes in Computer Science
year: 2025
bibkey: xiao2025visual
citations: 796
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.17650'}]
tags: [RAG, Training Techniques, Prompting, Tools, Evaluation, Transformer, Model
    Architecture, Fine Tuning, Datasets]
---
Parameter-efficient fine-tuning (PEFT) has emerged as a crucial approach for
adapting large vision transformers to downstream tasks without the prohibitive
computational costs of full fine-tuning. While existing visual prompt tuning
(VPT) methods have made significant strides, they predominantly rely on static,
domain-specific prompts that fail to capture the rich visual diversity within
individual instances. This paper introduces V\\(^2\\)APT (Visual Variational
Autoencoder Prompt Tuning), a novel framework that generates dynamic,
input-dependent prompts using a variational autoencoder architecture. By
learning a latent representation of image-specific features and decoding them
into customized prompts, V\\(^2\\)APT adapts to the unique visual characteristics
of each input. Extensive experiments on FGVC, HTA, and VTAB-1k benchmarks
demonstrate that our approach consistently outperforms state-of-the-art PEFT
methods. Notably, V\\(^2\\)APT achieves +3.2% improvement over VPT-Deep on HTA,
with an average performance gain of +2.0% across all three datasets.