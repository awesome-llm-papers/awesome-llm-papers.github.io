---
layout: publication
title: 'Visionts: Visual Masked Autoencoders Are Free-lunch Zero-shot Time Series
  Forecasters'
authors: Mouxiang Chen, Lefei Shen, Zhuo Li, Xiaoyun Joy Wang, Jianling Sun, Chenghao
  Liu
conference: No Venue
year: 2024
bibkey: chen2024visionts
additional_links: [{name: Code, url: 'https://github.com/Keytoyze/VisionTS'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/66d58e8d35c36f266f727c2e'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2408.17253'}]
tags: ["Time Series"]
short_authors: Chen et al.
---
Foundation models have emerged as a promising approach in time series forecasting (TSF). Existing approaches either fine-tune large language models (LLMs) or build large-scale time-series datasets to develop TSF foundation models. However, these methods face challenges due to the severe cross-domain gap or in-domain heterogeneity. In this paper, we explore a new road to building a TSF foundation model from rich and high-quality natural images, based on the intrinsic similarities between images and time series. To bridge the gap between the two domains, we reformulate the TSF task as an image reconstruction task, which is further processed by a visual masked autoencoder (MAE) self-supervised pre-trained on the ImageNet dataset. Surprisingly, without further adaptation in the time-series domain, the proposed VisionTS could achieve superior zero-shot forecasting performance compared to existing TSF foundation models. With minimal fine-tuning, VisionTS could further improve the forecasting and achieve state-of-the-art performance in most cases. These findings suggest that visual models could be a free lunch for TSF and highlight the potential for future cross-domain research between computer vision and TSF. Our code is publicly available at https://github.com/Keytoyze/VisionTS.

https://huggingface.co/discussions/paper/66d58e8d35c36f266f727c2e