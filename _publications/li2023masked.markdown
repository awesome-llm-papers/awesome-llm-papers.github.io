---
layout: publication
title: Masked Vision And Language Pre-training With Unimodal And Multimodal Contrastive
  Losses For Medical Visual Question Answering
authors: Pengfei Li, Gang Liu, Jinlong He, Zixu Zhao, Shenjun Zhong
conference: Arxiv
year: 2023
citations: 24
bibkey: li2023masked
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.05314'}, {name: Code,
    url: 'https://github.com/pengfeiliHEU/MUMC'}]
tags: [Masked Language Model, Training Techniques, RAG, Fine-Tuning, Pre-Training,
  BERT, Has Code, Multimodal Models, Language Modeling]
---
Medical visual question answering (VQA) is a challenging task that requires
answering clinical questions of a given medical image, by taking consider of
both visual and language information. However, due to the small scale of
training data for medical VQA, pre-training fine-tuning paradigms have been a
commonly used solution to improve model generalization performance. In this
paper, we present a novel self-supervised approach that learns unimodal and
multimodal feature representations of input images and text using medical image
caption datasets, by leveraging both unimodal and multimodal contrastive
losses, along with masked language modeling and image text matching as
pretraining objectives. The pre-trained model is then transferred to downstream
medical VQA tasks. The proposed approach achieves state-of-the-art (SOTA)
performance on three publicly available medical VQA datasets with significant
accuracy improvements of 2.2%, 14.7%, and 1.7% respectively. Besides, we
conduct a comprehensive analysis to validate the effectiveness of different
components of the approach and study different pre-training settings. Our codes
and models are available at https://github.com/pengfeiliHEU/MUMC.