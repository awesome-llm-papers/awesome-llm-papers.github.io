---
layout: publication
title: 'Yulan-mini: An Open Data-efficient Language Model'
authors: Yiwen Hu, Huatong Song, Jia Deng, Jiapeng Wang, Jie Chen, Kun Zhou, Yutao
  Zhu, Jinhao Jiang, Zican Dong, Wayne Xin Zhao, Ji-rong Wen
conference: No Venue
year: 2024
bibkey: hu2024yulan
additional_links: [{name: Code, url: 'https://github.com/RUC-GSAI/YuLan-Mini'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/676d2c65310ca4eb39741682'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2412.17743'}]
tags: ["Efficiency", "Has Code", "Training Techniques"]
short_authors: Hu et al.
---
Effective pre-training of large language models (LLMs) has been challenging due to the immense resource demands and the complexity of the technical processes involved. This paper presents a detailed technical report on YuLan-Mini, a highly capable base model with 2.42B parameters that achieves top-tier performance among models of similar parameter scale. Our pre-training approach focuses on enhancing training efficacy through three key technical contributions: an elaborate data pipeline combines data cleaning with data schedule strategies, a robust optimization method to mitigate training instability, and an effective annealing approach that incorporates targeted data selection and long context training. Remarkably, YuLan-Mini, trained on 1.08T tokens, achieves performance comparable to industry-leading models that require significantly more data. To facilitate reproduction, we release the full details of the data composition for each training phase. Project details can be accessed at the following link: https://github.com/RUC-GSAI/YuLan-Mini.

https://huggingface.co/discussions/paper/676d2c65310ca4eb39741682