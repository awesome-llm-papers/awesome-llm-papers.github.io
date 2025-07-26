---
layout: publication
title: 'Janusflow: Harmonizing Autoregression And Rectified Flow For Unified Multimodal
  Understanding And Generation'
authors: Yiyang Ma, Xingchao Liu, Xiaokang Chen, Wen Liu, Chengyue Wu, Zhiyu Wu, Zizheng
  Pan, Zhenda Xie, Haowei Zhang, Xingkai Yu, Liang Zhao, Yisong Wang, Jiaying Liu,
  Chong Ruan
conference: No Venue
year: 2024
bibkey: ma2024janusflow
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/673423259a3e8b8171a34bfe'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2411.07975'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Ma et al.
---
We present JanusFlow, a powerful framework that unifies image understanding and generation in a single model. JanusFlow introduces a minimalist architecture that integrates autoregressive language models with rectified flow, a state-of-the-art method in generative modeling. Our key finding demonstrates that rectified flow can be straightforwardly trained within the large language model framework, eliminating the need for complex architectural modifications. To further improve the performance of our unified model, we adopt two key strategies: (i) decoupling the understanding and generation encoders, and (ii) aligning their representations during unified training. Extensive experiments show that JanusFlow achieves comparable or superior performance to specialized models in their respective domains, while significantly outperforming existing unified approaches across standard benchmarks. This work represents a step toward more efficient and versatile vision-language models.

https://huggingface.co/discussions/paper/673423259a3e8b8171a34bfe