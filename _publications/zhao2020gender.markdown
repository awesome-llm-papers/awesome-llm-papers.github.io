---
layout: publication
title: Gender Bias In Multilingual Embeddings And Cross-lingual Transfer
authors: Jieyu Zhao, Subhabrata Mukherjee, Saghar Hosseini, Kai-wei Chang, Ahmed Hassan
  Awadallah
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: zhao2020gender
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.00699'}]
tags: ["Ethics & Fairness"]
short_authors: Zhao et al.
---
Multilingual representations embed words from many languages into a single
semantic space such that words with similar meanings are close to each other
regardless of the language. These embeddings have been widely used in various
settings, such as cross-lingual transfer, where a natural language processing
(NLP) model trained on one language is deployed to another language. While the
cross-lingual transfer techniques are powerful, they carry gender bias from the
source to target languages. In this paper, we study gender bias in multilingual
embeddings and how it affects transfer learning for NLP applications. We create
a multilingual dataset for bias analysis and propose several ways for
quantifying bias in multilingual representations from both the intrinsic and
extrinsic perspectives. Experimental results show that the magnitude of bias in
the multilingual representations changes differently when we align the
embeddings to different target spaces and that the alignment direction can also
have an influence on the bias in transfer learning. We further provide
recommendations for using the multilingual word representations for downstream
tasks.