---
layout: publication
title: Text Generation By Learning From Demonstrations
authors: Richard Yuanzhe Pang, He He
conference: Arxiv
year: 2020
citations: 28
bibkey: pang2020text
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.07839'}]
tags: [Ethics and Bias, GPT, Training Techniques, Reinforcement Learning, Agentic,
  Efficiency and Optimization, Language Modeling]
---
Current approaches to text generation largely rely on autoregressive models
and maximum likelihood estimation. This paradigm leads to (i) diverse but
low-quality samples due to mismatched learning objective and evaluation metric
(likelihood vs. quality) and (ii) exposure bias due to mismatched history
distributions (gold vs. model-generated). To alleviate these problems, we frame
text generation as an offline reinforcement learning (RL) problem with expert
demonstrations (i.e., the reference), where the goal is to maximize quality
given model-generated histories. We propose GOLD (generation by off-policy
learning from demonstrations): an easy-to-optimize algorithm that learns from
the demonstrations by importance weighting. Intuitively, GOLD upweights
confident tokens and downweights unconfident ones in the reference during
training, avoiding optimization issues faced by prior RL approaches that rely
on online data collection. According to both automatic and human evaluation,
models trained by GOLD outperform those trained by MLE and policy gradient on
summarization, question generation, and machine translation. Further, our
models are less sensitive to decoding algorithms and alleviate exposure bias.