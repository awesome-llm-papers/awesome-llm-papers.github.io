---
layout: publication
title: 'Uniworld: High-resolution Semantic Encoders For Unified Visual Understanding
  And Generation'
authors: Bin Lin, Zongjian Li, Xinhua Cheng, Yuwei Niu, Yang Ye, Xianyi He, Shenghai
  Yuan, Wangbo Yu, Shaodong Wang, Yunyang Ge, Yatian Pang, Li Yuan
conference: No Venue
year: 2025
bibkey: lin2025uniworld
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/683fae56c6b71c5994ccd548'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.03147'}]
tags: ["Applications", "Model Architecture", "Tools"]
short_authors: Lin et al.
---
Although existing unified models deliver strong performance on vision-language understanding and text-to-image generation, their models are limited in exploring image perception and manipulation tasks, which are urgently desired by users for wide applications. Recently, OpenAI released their powerful GPT-4o-Image model for comprehensive image perception and manipulation, achieving expressive capability and attracting community interests. By observing the performance of GPT-4o-Image in our carefully constructed experiments, we infer that GPT-4o-Image leverages features extracted by semantic encoders instead of VAE, while VAEs are considered essential components in many image manipulation models. Motivated by such inspiring observations, we present a unified generative framework named UniWorld based on semantic features provided by powerful visual-language models and contrastive semantic encoders. As a result, we build a strong unified model using only 1% amount of BAGEL's data, which consistently outperforms BAGEL on image editing benchmarks. UniWorld also maintains competitive image understanding and generation capabilities, achieving strong performance across multiple image perception tasks. We fully open-source our models, including model weights, training and evaluation scripts, and datasets.

https://huggingface.co/discussions/paper/683fae56c6b71c5994ccd548