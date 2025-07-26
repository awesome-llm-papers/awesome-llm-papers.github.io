---
layout: publication
title: Leveraging Passage Retrieval With Generative Models For Open Domain Question
  Answering
authors: Gautier Izacard, Edouard Grave
conference: 'Proceedings of the 16th Conference of the European Chapter of the Association
  for Computational Linguistics: Main Volume'
year: 2021
bibkey: izacard2020leveraging
citations: 553
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2007.01282'}]
tags: ["EACL"]
short_authors: Gautier Izacard, Edouard Grave
---
Generative models for open domain question answering have proven to be
competitive, without resorting to external knowledge. While promising, this
approach requires to use models with billions of parameters, which are
expensive to train and query. In this paper, we investigate how much these
models can benefit from retrieving text passages, potentially containing
evidence. We obtain state-of-the-art results on the Natural Questions and
TriviaQA open benchmarks. Interestingly, we observe that the performance of
this method significantly improves when increasing the number of retrieved
passages. This is evidence that generative models are good at aggregating and
combining evidence from multiple passages.