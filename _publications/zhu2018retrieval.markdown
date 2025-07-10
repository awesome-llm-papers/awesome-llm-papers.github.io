---
layout: publication
title: Retrieval-enhanced Adversarial Training For Neural Response Generation
authors: Qingfu Zhu, Lei Cui, Weinan Zhang, Furu Wei, Ting Liu
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2018
citations: 21
bibkey: zhu2018retrieval
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.04276'}]
tags: [Security, RAG, Tools, Training Techniques, Evaluation]
---
Dialogue systems are usually built on either generation-based or
retrieval-based approaches, yet they do not benefit from the advantages of
different models. In this paper, we propose a Retrieval-Enhanced Adversarial
Training (REAT) method for neural response generation. Distinct from existing
approaches, the REAT method leverages an encoder-decoder framework in terms of
an adversarial training paradigm, while taking advantage of N-best response
candidates from a retrieval-based system to construct the discriminator. An
empirical study on a large scale public available benchmark dataset shows that
the REAT method significantly outperforms the vanilla Seq2Seq model as well as
the conventional adversarial training approach.