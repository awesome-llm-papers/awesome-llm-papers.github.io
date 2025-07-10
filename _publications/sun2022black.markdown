---
layout: publication
title: Black-box Tuning For Language-model-as-a-service
authors: Tianxiang Sun, Yunfan Shao, Hong Qian, Xuanjing Huang, Xipeng Qiu
conference: Arxiv
year: 2022
citations: 55
bibkey: sun2022black
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2201.03514'}]
tags: [Model Architecture, GPT, Tools, In-Context Learning, Prompting, Efficiency
    and Optimization, BERT]
---
Extremely large pre-trained language models (PTMs) such as GPT-3 are usually
released as a service. It allows users to design task-specific prompts to query
the PTMs through some black-box APIs. In such a scenario, which we call
Language-Model-as-a-Service (LMaaS), the gradients of PTMs are usually
unavailable. Can we optimize the task prompts by only accessing the model
inference APIs? This paper proposes the black-box tuning framework to optimize
the continuous prompt prepended to the input text via derivative-free
optimization. Instead of optimizing in the original high-dimensional prompt
space, which is intractable for traditional derivative-free optimization, we
perform optimization in a randomly generated subspace due to the low intrinsic
dimensionality of large PTMs. The experimental results show that the black-box
tuning with RoBERTa on a few labeled samples not only significantly outperforms
manual prompt and GPT-3's in-context learning, but also surpasses the
gradient-based counterparts, i.e., prompt tuning and full model tuning.