---
layout: publication
title: 'Gector -- Grammatical Error Correction: Tag, Not Rewrite'
authors: Omelianchuk et al.
conference: Proceedings of the Fifteenth Workshop on Innovative Use of NLP for Building
  Educational Applications
year: 2020
bibkey: omelianchuk2020gector
citations: 89
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.12592'}]
tags: [Model Architecture, Applications, Transformer]
---
In this paper, we present a simple and efficient GEC sequence tagger using a
Transformer encoder. Our system is pre-trained on synthetic data and then
fine-tuned in two stages: first on errorful corpora, and second on a
combination of errorful and error-free parallel corpora. We design custom
token-level transformations to map input tokens to target corrections. Our best
single-model/ensemble GEC tagger achieves an \\(F_\{0.5\}\\) of 65.3/66.5 on
CoNLL-2014 (test) and \\(F_\{0.5\}\\) of 72.4/73.6 on BEA-2019 (test). Its inference
speed is up to 10 times as fast as a Transformer-based seq2seq GEC system. The
code and trained models are publicly available.