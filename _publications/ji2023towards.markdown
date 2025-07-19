---
layout: publication
title: 'Towards Better Instruction Following Language Models For Chinese: Investigating
  The Impact Of Training Data And Evaluation'
authors: Ji et al.
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2023
bibkey: ji2023towards
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.07854'}]
tags: [Model Architecture, Training Techniques, Efficiency And Optimization, Evaluation,
  ACL, GPT, Datasets, Reinforcement Learning]
---
Recently, significant public efforts have been directed towards developing
low-cost models with capabilities akin to ChatGPT, thereby fostering the growth
of open-source conversational models. However, there remains a scarcity of
comprehensive and in-depth evaluations of these models' performance. In this
study, we examine the influence of training data factors, including quantity,
quality, and linguistic distribution, on model performance. Our analysis is
grounded in several publicly accessible, high-quality instruction datasets, as
well as our own Chinese multi-turn conversations. We assess various models
using a evaluation set of 1,000 samples, encompassing nine real-world
scenarios. Our goal is to supplement manual evaluations with quantitative
analyses, offering valuable insights for the continued advancement of
open-source chat models. Furthermore, to enhance the performance and training
and inference efficiency of models in the Chinese domain, we extend the
vocabulary of LLaMA - the model with the closest open-source performance to
proprietary language models like GPT-3 - and conduct secondary pre-training on
3.4B Chinese words. We make our model, data, as well as code publicly
available.