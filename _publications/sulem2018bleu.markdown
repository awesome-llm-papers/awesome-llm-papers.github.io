---
layout: publication
title: BLEU Is Not Suitable For The Evaluation Of Text Simplification
authors: Sulem Elior, Abend Omri, Rappoport Ari
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: sulem2018bleu
citations: 139
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1810.05995'}]
tags: [Datasets, Evaluation, EMNLP]
---
BLEU is widely considered to be an informative metric for text-to-text
generation, including Text Simplification (TS). TS includes both lexical and
structural aspects. In this paper we show that BLEU is not suitable for the
evaluation of sentence splitting, the major structural simplification
operation. We manually compiled a sentence splitting gold standard corpus
containing multiple structural paraphrases, and performed a correlation
analysis with human judgments. We find low or no correlation between BLEU and
the grammaticality and meaning preservation parameters where sentence splitting
is involved. Moreover, BLEU often negatively correlates with simplicity,
essentially penalizing simpler sentences.