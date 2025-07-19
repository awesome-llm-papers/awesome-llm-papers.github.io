---
layout: publication
title: Analysis And Prediction Of NLP Models Via Task Embeddings
authors: Sileo Damien, Moens Marie-francine
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2021
bibkey: sileo2021analysis
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.05647'}]
tags: [EMNLP, Evaluation, Transformer, Model Architecture, Fine Tuning, Datasets]
---
Task embeddings are low-dimensional representations that are trained to
capture task properties. In this paper, we propose MetaEval, a collection of
\\(101\\) NLP tasks. We fit a single transformer to all MetaEval tasks jointly
while conditioning it on learned embeddings. The resulting task embeddings
enable a novel analysis of the space of tasks. We then show that task aspects
can be mapped to task embeddings for new tasks without using any annotated
examples.
  Predicted embeddings can modulate the encoder for zero-shot inference and
outperform a zero-shot baseline on GLUE tasks. The provided multitask setup can
function as a benchmark for future transfer learning research.