---
layout: publication
title: Non-autoregressive Neural Machine Translation
authors: Gu et al.
conference: Arxiv
year: 2017
bibkey: gu2017non
citations: 471
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1711.02281'}]
tags: [Training Techniques, Distillation, GPT, Transformer, Model Architecture, Efficiency
    And Optimization, Language Modeling, Reinforcement Learning, Fine Tuning, SLT]
---
Existing approaches to neural machine translation condition each output word
on previously generated outputs. We introduce a model that avoids this
autoregressive property and produces its outputs in parallel, allowing an order
of magnitude lower latency during inference. Through knowledge distillation,
the use of input token fertilities as a latent variable, and policy gradient
fine-tuning, we achieve this at a cost of as little as 2.0 BLEU points relative
to the autoregressive Transformer network used as a teacher. We demonstrate
substantial cumulative improvements associated with each of the three aspects
of our training strategy, and validate our approach on IWSLT 2016
English-German and two WMT language pairs. By sampling fertilities in parallel
at inference time, our non-autoregressive model achieves near-state-of-the-art
performance of 29.8 BLEU on WMT 2016 English-Romanian.