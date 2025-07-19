---
layout: publication
title: Neural Phrase-to-phrase Machine Translation
authors: Feng et al.
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: feng2018neural
citations: 497
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1811.02172'}]
tags: [Training Techniques, Attention Mechanism, EMNLP, Evaluation, Transformer, Model
    Architecture, Datasets]
---
In this paper, we propose Neural Phrase-to-Phrase Machine Translation
(NP\\(^2\\)MT). Our model uses a phrase attention mechanism to discover relevant
input (source) segments that are used by a decoder to generate output (target)
phrases. We also design an efficient dynamic programming algorithm to decode
segments that allows the model to be trained faster than the existing neural
phrase-based machine translation method by Huang et al. (2018). Furthermore,
our method can naturally integrate with external phrase dictionaries during
decoding. Empirical experiments show that our method achieves comparable
performance with the state-of-the art methods on benchmark datasets. However,
when the training and testing data are from different distributions or domains,
our method performs better.