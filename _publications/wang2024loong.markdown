---
layout: publication
title: 'Loong: Generating Minute-level Long Videos With Autoregressive Language Models'
authors: Yuqing Wang, Tianwei Xiong, Daquan Zhou, Zhijie Lin, Yang Zhao, Bingyi Kang,
  Jiashi Feng, Xihui Liu
conference: No Venue
year: 2024
bibkey: wang2024loong
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2410.02757'}]
tags: ["Has Code"]
short_authors: Wang et al.
---
It is desirable but challenging to generate content-rich long videos in the scale of minutes. Autoregressive large language models (LLMs) have achieved great success in generating coherent and long sequences of tokens in the domain of natural language processing, while the exploration of autoregressive LLMs for video generation is limited to generating short videos of several seconds. In this work, we conduct a deep analysis of the challenges that prevent autoregressive LLM-based video generators from generating long videos. Based on the observations and analysis, we propose Loong, a new autoregressive LLM-based video generator that can generate minute-long videos. Specifically, we model the text tokens and video tokens as a unified sequence for autoregressive LLMs and train the model from scratch. We propose progressive short-to-long training with a loss re-weighting scheme to mitigate the loss imbalance problem for long video training. We further investigate inference strategies, including video token re-encoding and sampling strategies, to diminish error accumulation during inference. Our proposed Loong can be trained on 10-second videos and be extended to generate minute-level long videos conditioned on text prompts, as demonstrated by the results. More samples are available at: https://epiphqny.github.io/Loong-video.

https://huggingface.co/discussions/paper/66ff59141687036580ad3b19