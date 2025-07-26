---
layout: publication
title: Cloze-driven Pretraining Of Self-attention Networks
authors: Alexei Baevski, Sergey Edunov, Yinhan Liu, Luke Zettlemoyer, Michael Auli
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: baevski2019cloze
citations: 203
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1903.07785'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Baevski et al.
---
We present a new approach for pretraining a bi-directional transformer model
that provides significant performance gains across a variety of language
understanding problems. Our model solves a cloze-style word reconstruction
task, where each word is ablated and must be predicted given the rest of the
text. Experiments demonstrate large performance gains on GLUE and new state of
the art results on NER as well as constituency parsing benchmarks, consistent
with the concurrently introduced BERT model. We also present a detailed
analysis of a number of factors that contribute to effective pretraining,
including data domain and size, model capacity, and variations on the cloze
objective.