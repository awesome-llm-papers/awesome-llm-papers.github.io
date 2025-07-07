---
layout: publication
title: 'From Zero To Hero: On The Limitations Of Zero-shot Cross-lingual Transfer
  With Multilingual Transformers'
authors: "Anne Lauscher, Vinit Ravishankar, Ivan Vuli\u0107, Goran Glava\u0161"
conference: Arxiv
year: 2020
citations: 45
bibkey: lauscher2020from
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.00633'}]
tags: [Training Techniques, Transformer, Few-Shot, Fine-Tuning, BERT, Language Modeling,
  Model Architecture]
---
Massively multilingual transformers pretrained with language modeling
objectives (e.g., mBERT, XLM-R) have become a de facto default transfer
paradigm for zero-shot cross-lingual transfer in NLP, offering unmatched
transfer performance. Current downstream evaluations, however, verify their
efficacy predominantly in transfer settings involving languages with sufficient
amounts of pretraining data, and with lexically and typologically close
languages. In this work, we analyze their limitations and show that
cross-lingual transfer via massively multilingual transformers, much like
transfer via cross-lingual word embeddings, is substantially less effective in
resource-lean scenarios and for distant languages. Our experiments,
encompassing three lower-level tasks (POS tagging, dependency parsing, NER), as
well as two high-level semantic tasks (NLI, QA), empirically correlate transfer
performance with linguistic similarity between the source and target languages,
but also with the size of pretraining corpora of target languages. We also
demonstrate a surprising effectiveness of inexpensive few-shot transfer (i.e.,
fine-tuning on a few target-language instances after fine-tuning in the source)
across the board. This suggests that additional research efforts should be
invested to reach beyond the limiting zero-shot conditions.