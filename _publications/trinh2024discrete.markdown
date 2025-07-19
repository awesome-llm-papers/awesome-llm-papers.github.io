---
layout: publication
title: Discrete Multimodal Transformers With A Pretrained Large Language Model For
  Mixed-supervision Speech Processing
authors: Trinh et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2024
bibkey: trinh2024discrete
citations: 339
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.06582'}]
tags: [Masked Language Model, Model Architecture, Training Techniques, Tokenization,
  ACL, Transformer, Multimodal Models, Datasets]
---
Recent work on discrete speech tokenization has paved the way for models that
can seamlessly perform multiple tasks across modalities, e.g., speech
recognition, text to speech, speech to speech translation. Moreover, large
language models (LLMs) pretrained from vast text corpora contain rich
linguistic information that can improve accuracy in a variety of tasks. In this
paper, we present a decoder-only Discrete Multimodal Language Model (DMLM),
which can be flexibly applied to multiple tasks (ASR, T2S, S2TT, etc.) and
modalities (text, speech, vision). We explore several critical aspects of
discrete multi-modal models, including the loss function, weight
initialization, mixed training supervision, and codebook. Our results show that
DMLM benefits significantly, across multiple tasks and datasets, from a
combination of supervised and unsupervised training. Moreover, for ASR, it
benefits from initializing DMLM from a pretrained LLM, and from a codebook
derived from Whisper activations.