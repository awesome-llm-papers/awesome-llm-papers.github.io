---
layout: publication
title: An Operation Sequence Model For Explainable Neural Machine Translation
authors: Stahlberg Felix, Saunders Danielle, Byrne Bill
conference: 'Proceedings of the 2018 EMNLP Workshop BlackboxNLP: Analyzing and Interpreting
  Neural Networks for NLP'
year: 2018
bibkey: stahlberg2018operation
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.09688'}]
tags: [Interpretability And Explainability, Model Architecture, EMNLP, Transformer]
---
We propose to achieve explainable neural machine translation (NMT) by
changing the output representation to explain itself. We present a novel
approach to NMT which generates the target sentence by monotonically walking
through the source sentence. Word reordering is modeled by operations which
allow setting markers in the target sentence and move a target-side write head
between those markers. In contrast to many modern neural models, our system
emits explicit word alignment information which is often crucial to practical
machine translation as it improves explainability. Our technique can outperform
a plain text system in terms of BLEU score under the recent Transformer
architecture on Japanese-English and Portuguese-English, and is within 0.5 BLEU
difference on Spanish-English.