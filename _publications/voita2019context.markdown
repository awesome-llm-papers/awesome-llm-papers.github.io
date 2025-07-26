---
layout: publication
title: Context-aware Monolingual Repair For Neural Machine Translation
authors: Elena Voita, Rico Sennrich, Ivan Titov
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: voita2019context
citations: 100
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.01383'}]
tags: ["EMNLP", "Training Techniques"]
short_authors: Elena Voita, Rico Sennrich, Ivan Titov
---
Modern sentence-level NMT systems often produce plausible translations of
isolated sentences. However, when put in context, these translations may end up
being inconsistent with each other. We propose a monolingual DocRepair model to
correct inconsistencies between sentence-level translations. DocRepair performs
automatic post-editing on a sequence of sentence-level translations, refining
translations of sentences in context of each other. For training, the DocRepair
model requires only monolingual document-level data in the target language. It
is trained as a monolingual sequence-to-sequence model that maps inconsistent
groups of sentences into consistent ones. The consistent groups come from the
original training data; the inconsistent groups are obtained by sampling
round-trip translations for each isolated sentence. We show that this approach
successfully imitates inconsistencies we aim to fix: using contrastive
evaluation, we show large improvements in the translation of several contextual
phenomena in an English-Russian translation task, as well as improvements in
the BLEU score. We also conduct a human evaluation and show a strong preference
of the annotators to corrected translations over the baseline ones. Moreover,
we analyze which discourse phenomena are hard to capture using monolingual data
only.