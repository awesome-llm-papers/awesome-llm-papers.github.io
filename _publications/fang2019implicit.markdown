---
layout: publication
title: Implicit Deep Latent Variable Models For Text Generation
authors: Fang et al.
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: fang2019implicit
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.11527'}]
tags: [Language Modeling, EMNLP]
---
Deep latent variable models (LVM) such as variational auto-encoder (VAE) have
recently played an important role in text generation. One key factor is the
exploitation of smooth latent structures to guide the generation. However, the
representation power of VAEs is limited due to two reasons: (1) the Gaussian
assumption is often made on the variational posteriors; and meanwhile (2) a
notorious "posterior collapse" issue occurs. In this paper, we advocate
sample-based representations of variational distributions for natural language,
leading to implicit latent features, which can provide flexible representation
power compared with Gaussian-based posteriors. We further develop an LVM to
directly match the aggregated posterior to the prior. It can be viewed as a
natural extension of VAEs with a regularization of maximizing mutual
information, mitigating the "posterior collapse" issue. We demonstrate the
effectiveness and versatility of our models in various text generation
scenarios, including language modeling, unaligned style transfer, and dialog
response generation. The source code to reproduce our experimental results is
available on GitHub.