---
layout: publication
title: Frequency Autoregressive Image Generation With Continuous Tokens
authors: Yu et al.
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: yu2025frequency
citations: 91
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.05305'}]
tags: [Training Techniques, GPT, CVPR, Evaluation, Efficiency And Optimization, Language
    Modeling, Quantization, Datasets]
---
Autoregressive (AR) models for image generation typically adopt a two-stage
paradigm of vector quantization and raster-scan ``next-token prediction",
inspired by its great success in language modeling. However, due to the huge
modality gap, image autoregressive models may require a systematic reevaluation
from two perspectives: tokenizer format and regression direction. In this
paper, we introduce the frequency progressive autoregressive (\textbf\{FAR\})
paradigm and instantiate FAR with the continuous tokenizer. Specifically, we
identify spectral dependency as the desirable regression direction for FAR,
wherein higher-frequency components build upon the lower one to progressively
construct a complete image. This design seamlessly fits the causality
requirement for autoregressive models and preserves the unique spatial locality
of image data. Besides, we delve into the integration of FAR and the continuous
tokenizer, introducing a series of techniques to address optimization
challenges and improve the efficiency of training and inference processes. We
demonstrate the efficacy of FAR through comprehensive experiments on the
ImageNet dataset and verify its potential on text-to-image generation.