---
layout: publication
title: 'Greekbart: The First Pretrained Greek Sequence-to-sequence Model'
authors: Evdaimon et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2023
bibkey: evdaimon2023greekbart
citations: 222
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.00869'}]
tags: [Model Architecture, Fine Tuning, BERT, ACL, EMNLP, GPT, Transformer, Datasets]
---
The era of transfer learning has revolutionized the fields of Computer Vision
and Natural Language Processing, bringing powerful pretrained models with
exceptional performance across a variety of tasks. Specifically, Natural
Language Processing tasks have been dominated by transformer-based language
models. In Natural Language Inference and Natural Language Generation tasks,
the BERT model and its variants, as well as the GPT model and its successors,
demonstrated exemplary performance. However, the majority of these models are
pretrained and assessed primarily for the English language or on a multilingual
corpus. In this paper, we introduce GreekBART, the first Seq2Seq model based on
BART-base architecture and pretrained on a large-scale Greek corpus. We
evaluate and compare GreekBART against BART-random, Greek-BERT, and XLM-R on a
variety of discriminative tasks. In addition, we examine its performance on two
NLG tasks from GreekSUM, a newly introduced summarization dataset for the Greek
language. The model, the code, and the new summarization dataset will be
publicly available.