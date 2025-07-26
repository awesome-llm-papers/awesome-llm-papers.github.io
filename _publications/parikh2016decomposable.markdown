---
layout: publication
title: A Decomposable Attention Model For Natural Language Inference
authors: "Ankur P. Parikh, Oscar T\xE4ckstr\xF6m, Dipanjan Das, Jakob Uszkoreit"
conference: Proceedings of the 2016 Conference on Empirical Methods in Natural Language
  Processing
year: 2016
bibkey: parikh2016decomposable
citations: 1412
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.01933'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Parikh et al.
---
We propose a simple neural architecture for natural language inference. Our
approach uses attention to decompose the problem into subproblems that can be
solved separately, thus making it trivially parallelizable. On the Stanford
Natural Language Inference (SNLI) dataset, we obtain state-of-the-art results
with almost an order of magnitude fewer parameters than previous work and
without relying on any word-order information. Adding intra-sentence attention
that takes a minimum amount of order into account yields further improvements.