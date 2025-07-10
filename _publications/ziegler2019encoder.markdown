---
layout: publication
title: Encoder-agnostic Adaptation For Conditional Language Generation
authors: Zachary M. Ziegler, Luke Melas-kyriazi, Sebastian Gehrmann, Alexander M.
  Rush
conference: Arxiv
year: 2019
citations: 27
bibkey: ziegler2019encoder
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.06938'}]
tags: [Language Modeling, Model Architecture, Attention Mechanism, Transformer, Reinforcement
    Learning]
---
Large pretrained language models have changed the way researchers approach
discriminative natural language understanding tasks, leading to the dominance
of approaches that adapt a pretrained model for arbitrary downstream tasks.
However it is an open-question how to use similar techniques for language
generation. Early results in the encoder-agnostic setting have been mostly
negative. In this work we explore methods for adapting a pretrained language
model to arbitrary conditional input. We observe that pretrained transformer
models are sensitive to large parameter changes during tuning. We therefore
propose an adaptation that directly injects arbitrary conditioning into self
attention, an approach we call pseudo self attention. Through experiments on
four diverse conditional text generation tasks we show that this
encoder-agnostic technique outperforms strong baselines, produces coherent
generations, and is data efficient.