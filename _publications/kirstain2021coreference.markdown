---
layout: publication
title: Coreference Resolution Without Span Representations
authors: Yuval Kirstain, Ori Ram, Omer Levy
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 2: Short Papers)'
year: 2021
bibkey: kirstain2021coreference
citations: 60
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2101.00434'}]
tags: ["Model Architecture"]
short_authors: Yuval Kirstain, Ori Ram, Omer Levy
---
The introduction of pretrained language models has reduced many complex
task-specific NLP models to simple lightweight layers. An exception to this
trend is coreference resolution, where a sophisticated task-specific model is
appended to a pretrained transformer encoder. While highly effective, the model
has a very large memory footprint -- primarily due to dynamically-constructed
span and span-pair representations -- which hinders the processing of complete
documents and the ability to train on multiple instances in a single batch. We
introduce a lightweight end-to-end coreference model that removes the
dependency on span representations, handcrafted features, and heuristics. Our
model performs competitively with the current standard model, while being
simpler and more efficient.