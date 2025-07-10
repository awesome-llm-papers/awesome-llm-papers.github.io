---
layout: publication
title: 'Retromae: Pre-training Retrieval-oriented Language Models Via Masked Auto-encoder'
authors: Shitao Xiao, Zheng Liu, Yingxia Shao, Zhao Cao
conference: Proceedings of the 2022 Conference on Empirical Methods in Natural Language
  Processing
year: 2022
citations: 32
bibkey: xiao2022pre
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.12035'}, {name: Code,
    url: 'https://github.com/staoxiao/RetroMAE'}]
tags: [Language Modeling, Has Code, Model Architecture, Transformer, Masked Language
    Model, Tools, Pre-Training, BERT, Training Techniques, Evaluation]
---
Despite pre-training's progress in many important NLP tasks, it remains to
explore effective pre-training strategies for dense retrieval. In this paper,
we propose RetroMAE, a new retrieval oriented pre-training paradigm based on
Masked Auto-Encoder (MAE). RetroMAE is highlighted by three critical designs.
1) A novel MAE workflow, where the input sentence is polluted for encoder and
decoder with different masks. The sentence embedding is generated from the
encoder's masked input; then, the original sentence is recovered based on the
sentence embedding and the decoder's masked input via masked language modeling.
2) Asymmetric model structure, with a full-scale BERT like transformer as
encoder, and a one-layer transformer as decoder. 3) Asymmetric masking ratios,
with a moderate ratio for encoder: 15~30%, and an aggressive ratio for decoder:
50~70%. Our framework is simple to realize and empirically competitive: the
pre-trained models dramatically improve the SOTA performances on a wide range
of dense retrieval benchmarks, like BEIR and MS MARCO. The source code and
pre-trained models are made publicly available at
https://github.com/staoxiao/RetroMAE so as to inspire more interesting
research.