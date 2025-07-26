---
layout: publication
title: 'PAWS-X: A Cross-lingual Adversarial Dataset For Paraphrase Identification'
authors: Yinfei Yang, Yuan Zhang, Chris Tar, Jason Baldridge
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: yang2019paws
citations: 226
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.11828'}]
tags: ["Datasets", "EMNLP", "Evaluation"]
short_authors: Yang et al.
---
Most existing work on adversarial data generation focuses on English. For
example, PAWS (Paraphrase Adversaries from Word Scrambling) consists of
challenging English paraphrase identification pairs from Wikipedia and Quora.
We remedy this gap with PAWS-X, a new dataset of 23,659 human translated PAWS
evaluation pairs in six typologically distinct languages: French, Spanish,
German, Chinese, Japanese, and Korean. We provide baseline numbers for three
models with different capacity to capture non-local context and sentence
structure, and using different multilingual training and evaluation regimes.
Multilingual BERT fine-tuned on PAWS English plus machine-translated data
performs the best, with a range of 83.1-90.8 accuracy across the non-English
languages and an average accuracy gain of 23% over the next best model. PAWS-X
shows the effectiveness of deep, multilingual pre-training while also leaving
considerable headroom as a new challenge to drive multilingual research that
better captures structure and contextual information.