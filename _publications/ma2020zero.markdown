---
layout: publication
title: Zero-shot Neural Passage Retrieval Via Domain-targeted Synthetic Question Generation
authors: Ji Ma, Ivan Korotkov, Yinfei Yang, Keith Hall, Ryan Mcdonald
conference: 'Proceedings of the 16th Conference of the European Chapter of the Association
  for Computational Linguistics: Main Volume'
year: 2021
bibkey: ma2020zero
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.14503'}]
tags: ["EACL", "Training Techniques"]
short_authors: Ma et al.
---
A major obstacle to the wide-spread adoption of neural retrieval models is
that they require large supervised training sets to surpass traditional
term-based techniques, which are constructed from raw corpora. In this paper,
we propose an approach to zero-shot learning for passage retrieval that uses
synthetic question generation to close this gap. The question generation system
is trained on general domain data, but is applied to documents in the targeted
domain. This allows us to create arbitrarily large, yet noisy, question-passage
relevance pairs that are domain specific. Furthermore, when this is coupled
with a simple hybrid term-neural model, first-stage retrieval performance can
be improved further. Empirically, we show that this is an effective strategy
for building neural passage retrieval models in the absence of large training
corpora. Depending on the domain, this technique can even approach the accuracy
of supervised models.