---
layout: publication
title: 'SMART: Robust And Efficient Fine-tuning For Pre-trained Natural Language Models
  Through Principled Regularized Optimization'
authors: Haoming Jiang, Pengcheng He, Weizhu Chen, Xiaodong Liu, Jianfeng Gao, Tuo
  Zhao
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: jiang2019smart
citations: 320
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.03437'}]
tags: ["Fine-Tuning", "Tools", "Training Techniques"]
short_authors: Jiang et al.
---
Transfer learning has fundamentally changed the landscape of natural language
processing (NLP) research. Many existing state-of-the-art models are first
pre-trained on a large text corpus and then fine-tuned on downstream tasks.
However, due to limited data resources from downstream tasks and the extremely
large capacity of pre-trained models, aggressive fine-tuning often causes the
adapted model to overfit the data of downstream tasks and forget the knowledge
of the pre-trained model. To address the above issue in a more principled
manner, we propose a new computational framework for robust and efficient
fine-tuning for pre-trained language models. Specifically, our proposed
framework contains two important ingredients: 1. Smoothness-inducing
regularization, which effectively manages the capacity of the model; 2. Bregman
proximal point optimization, which is a class of trust-region methods and can
prevent knowledge forgetting. Our experiments demonstrate that our proposed
method achieves the state-of-the-art performance on multiple NLP benchmarks.