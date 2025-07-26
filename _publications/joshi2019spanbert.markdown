---
layout: publication
title: 'Spanbert: Improving Pre-training By Representing And Predicting Spans'
authors: Mandar Joshi, Danqi Chen, Yinhan Liu, Daniel S. Weld, Luke Zettlemoyer, Omer
  Levy
conference: Transactions of the Association for Computational Linguistics
year: 2020
bibkey: joshi2019spanbert
citations: 1696
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1907.10529'}]
tags: ["Model Architecture", "TACL", "Training Techniques"]
short_authors: Joshi et al.
---
We present SpanBERT, a pre-training method that is designed to better
represent and predict spans of text. Our approach extends BERT by (1) masking
contiguous random spans, rather than random tokens, and (2) training the span
boundary representations to predict the entire content of the masked span,
without relying on the individual token representations within it. SpanBERT
consistently outperforms BERT and our better-tuned baselines, with substantial
gains on span selection tasks such as question answering and coreference
resolution. In particular, with the same training data and model size as
BERT-large, our single model obtains 94.6% and 88.7% F1 on SQuAD 1.1 and 2.0,
respectively. We also achieve a new state of the art on the OntoNotes
coreference resolution task (79.6% F1), strong performance on the TACRED
relation extraction benchmark, and even show gains on GLUE.