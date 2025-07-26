---
layout: publication
title: Investigating Multilingual NMT Representations At Scale
authors: Sneha Reddy Kudugunta, Ankur Bapna, Isaac Caswell, Naveen Arivazhagan, Orhan
  Firat
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: kudugunta2019investigating
citations: 108
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.02197'}]
tags: ["EMNLP"]
short_authors: Kudugunta et al.
---
Multilingual Neural Machine Translation (NMT) models have yielded large
empirical success in transfer learning settings. However, these black-box
representations are poorly understood, and their mode of transfer remains
elusive. In this work, we attempt to understand massively multilingual NMT
representations (with 103 languages) using Singular Value Canonical Correlation
Analysis (SVCCA), a representation similarity framework that allows us to
compare representations across different languages, layers and models. Our
analysis validates several empirical results and long-standing intuitions, and
unveils new observations regarding how representations evolve in a multilingual
translation model. We draw three major conclusions from our analysis, with
implications on cross-lingual transfer learning: (i) Encoder representations of
different languages cluster based on linguistic similarity, (ii)
Representations of a source language learned by the encoder are dependent on
the target language, and vice-versa, and (iii) Representations of high resource
and/or linguistically similar languages are more robust when fine-tuning on an
arbitrary language pair, which is critical to determining how much
cross-lingual transfer can be expected in a zero or few-shot setting. We
further connect our findings with existing empirical observations in
multilingual NMT and transfer learning.