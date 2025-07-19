---
layout: publication
title: 'Formnet: Structural Encoding Beyond Sequential Modeling In Form Document Information
  Extraction'
authors: Lee et al.
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: lee2022formnet
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.08411'}]
tags: [Model Architecture, Training Techniques, Time Series, Evaluation, ACL, RAG,
  Datasets, Attention Mechanism]
---
Sequence modeling has demonstrated state-of-the-art performance on natural
language and document understanding tasks. However, it is challenging to
correctly serialize tokens in form-like documents in practice due to their
variety of layout patterns. We propose FormNet, a structure-aware sequence
model to mitigate the suboptimal serialization of forms. First, we design Rich
Attention that leverages the spatial relationship between tokens in a form for
more precise attention score calculation. Second, we construct Super-Tokens for
each word by embedding representations from their neighboring tokens through
graph convolutions. FormNet therefore explicitly recovers local syntactic
information that may have been lost during serialization. In experiments,
FormNet outperforms existing methods with a more compact model size and less
pre-training data, establishing new state-of-the-art performance on CORD, FUNSD
and Payment benchmarks.