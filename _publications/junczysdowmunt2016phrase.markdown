---
layout: publication
title: Phrase-based Machine Translation Is State-of-the-art For Automatic Grammatical
  Error Correction
authors: Marcin Junczys-dowmunt, Roman Grundkiewicz
conference: Proceedings of the 2016 Conference on Empirical Methods in Natural Language
  Processing
year: 2016
bibkey: junczysdowmunt2016phrase
citations: 120
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1605.06353'}]
tags: ["EMNLP", "Evaluation"]
short_authors: Marcin Junczys-dowmunt, Roman Grundkiewicz
---
In this work, we study parameter tuning towards the M^2 metric, the standard
metric for automatic grammar error correction (GEC) tasks. After implementing
M^2 as a scorer in the Moses tuning framework, we investigate interactions of
dense and sparse features, different optimizers, and tuning strategies for the
CoNLL-2014 shared task. We notice erratic behavior when optimizing sparse
feature weights with M^2 and offer partial solutions. We find that a bare-bones
phrase-based SMT setup with task-specific parameter-tuning outperforms all
previously published results for the CoNLL-2014 test set by a large margin
(46.37% M^2 over previously 41.75%, by an SMT system with neural features)
while being trained on the same, publicly available data. Our newly introduced
dense and sparse features widen that gap, and we improve the state-of-the-art
to 49.49% M^2.