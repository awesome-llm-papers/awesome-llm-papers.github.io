---
layout: publication
title: 'POINTS1.5: Building A Vision-language Model Towards Real World Applications'
authors: Yuan Liu, Le Tian, Xiao Zhou, Xinyu Gao, Kavio Yu, Yang Yu, Jie Zhou
conference: No Venue
year: 2024
bibkey: liu2024points1
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/675a62927f9a1b78132efc6f'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2412.08443'}]
tags: ["Applications"]
short_authors: Liu et al.
---
Vision-language models have made significant strides recently, demonstrating superior performance across a range of tasks, e.g. optical character recognition and complex diagram analysis. Building on this trend, we introduce a new vision-language model, POINTS1.5, designed to excel in various real-world applications. POINTS1.5 is an enhancement of POINTS1.0 and incorporates several key innovations: i) We replace the original CLIP vision encoder, which had a fixed image resolution, with a NaViT-style vision encoder that supports native dynamic high resolution. This allows POINTS1.5 to process images of any resolution without needing to split them into tiles. ii) We add bilingual support to POINTS1.5, significantly enhancing its capability in Chinese. Due to the scarcity of open-source Chinese datasets for vision-language models, we collect numerous images from the Internet and annotate them using a combination of manual and automatic methods. iii) We propose a set of rigorous filtering methods for visual instruction tuning datasets. We comprehensively evaluate all these filtering methods, and choose the most effective ones to obtain the final visual instruction tuning set. Thanks to these innovations, POINTS1.5 significantly outperforms POINTS1.0 and demonstrates strong performance across a range of real-world applications. Notably, POINTS1.5-7B is trained on fewer than 4 billion tokens and ranks first on the OpenCompass leaderboard among models with fewer than 10 billion parameters

https://huggingface.co/discussions/paper/675a62927f9a1b78132efc6f