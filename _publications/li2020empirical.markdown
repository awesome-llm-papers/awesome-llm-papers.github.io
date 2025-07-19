---
layout: publication
title: An Empirical Investigation Of Pre-trained Transformer Language Models For Open-domain
  Dialogue Generation
authors: Li Piji
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: li2020empirical
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2003.04195'}]
tags: [Training Techniques, EMNLP, Masked Language Model, Evaluation, Transformer,
  Model Architecture, Language Modeling, Fine Tuning]
---
We present an empirical investigation of pre-trained Transformer-based
auto-regressive language models for the task of open-domain dialogue
generation. Training paradigm of pre-training and fine-tuning is employed to
conduct the parameter learning. Corpora of News and Wikipedia in Chinese and
English are collected for the pre-training stage respectively. Dialogue context
and response are concatenated into a single sequence utilized as the input of
the models during the fine-tuning stage. A weighted joint prediction paradigm
for both context and response is designed to evaluate the performance of models
with or without the loss term for context prediction. Various of decoding
strategies such as greedy search, beam search, top-k sampling, etc. are
employed to conduct the response text generation. Extensive experiments are
conducted on the typical single-turn and multi-turn dialogue corpora such as
Weibo, Douban, Reddit, DailyDialog, and Persona-Chat. Detailed numbers of
automatic evaluation metrics on relevance and diversity of the generated
results for the languages models as well as the baseline approaches are
reported.