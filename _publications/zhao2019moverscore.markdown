---
layout: publication
title: 'Moverscore: Text Generation Evaluating With Contextualized Embeddings And
  Earth Mover Distance'
authors: Wei Zhao, Maxime Peyrard, Fei Liu, Yang Gao, Christian M. Meyer, Steffen
  Eger
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: zhao2019moverscore
citations: 437
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.02622'}]
tags: ["EMNLP", "Evaluation"]
short_authors: Zhao et al.
---
A robust evaluation metric has a profound impact on the development of text
generation systems. A desirable metric compares system output against
references based on their semantics rather than surface forms. In this paper we
investigate strategies to encode system and reference texts to devise a metric
that shows a high correlation with human judgment of text quality. We validate
our new metric, namely MoverScore, on a number of text generation tasks
including summarization, machine translation, image captioning, and
data-to-text generation, where the outputs are produced by a variety of neural
and non-neural systems. Our findings suggest that metrics combining
contextualized representations with a distance measure perform the best. Such
metrics also demonstrate strong generalization capability across tasks. For
ease-of-use we make our metrics available as web service.