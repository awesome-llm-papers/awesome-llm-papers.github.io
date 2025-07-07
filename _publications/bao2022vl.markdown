---
layout: publication
title: 'Vl-beit: Generative Vision-language Pretraining'
authors: Hangbo Bao, Wenhui Wang, Li Dong, Furu Wei
conference: Arxiv
year: 2022
citations: 21
bibkey: bao2022vl
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2206.01127'}]
tags: [Masked Language Model, Training Techniques, Transformer, BERT, Multimodal Models,
  Language Modeling, Model Architecture]
---
We introduce a vision-language foundation model called VL-BEiT, which is a
bidirectional multimodal Transformer learned by generative pretraining. Our
minimalist solution conducts masked prediction on both monomodal and multimodal
data with a shared Transformer. Specifically, we perform masked vision-language
modeling on image-text pairs, masked language modeling on texts, and masked
image modeling on images. VL-BEiT is learned from scratch with one unified
pretraining task, one shared backbone, and one-stage training. Our method is
conceptually simple and empirically effective. Experimental results show that
VL-BEiT obtains strong results on various vision-language benchmarks, such as
visual question answering, visual reasoning, and image-text retrieval.
Moreover, our method learns transferable visual features, achieving competitive
performance on image classification, and semantic segmentation.