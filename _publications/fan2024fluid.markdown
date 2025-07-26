---
layout: publication
title: 'Fluid: Scaling Autoregressive Text-to-image Generative Models With Continuous
  Tokens'
authors: Lijie Fan, Tianhong Li, Siyang Qin, Yuanzhen Li, Chen Sun, Michael Rubinstein,
  Deqing Sun, Kaiming He, Yonglong Tian
conference: No Venue
year: 2024
bibkey: fan2024fluid
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2410.13863'}]
tags: ["Model Architecture"]
short_authors: Fan et al.
---
Scaling up autoregressive models in vision has not proven as beneficial as in large language models. In this work, we investigate this scaling problem in the context of text-to-image generation, focusing on two critical factors: whether models use discrete or continuous tokens, and whether tokens are generated in a random or fixed raster order using BERT- or GPT-like transformer architectures. Our empirical results show that, while all models scale effectively in terms of validation loss, their evaluation performance -- measured by FID, GenEval score, and visual quality -- follows different trends. Models based on continuous tokens achieve significantly better visual quality than those using discrete tokens. Furthermore, the generation order and attention mechanisms significantly affect the GenEval score: random-order models achieve notably better GenEval scores compared to raster-order models. Inspired by these findings, we train Fluid, a random-order autoregressive model on continuous tokens. Fluid 10.5B model achieves a new state-of-the-art zero-shot FID of 6.16 on MS-COCO 30K, and 0.69 overall score on the GenEval benchmark. We hope our findings and results will encourage future efforts to further bridge the scaling gap between vision and language models.

https://huggingface.co/discussions/paper/6712be0767f2290f568956d5