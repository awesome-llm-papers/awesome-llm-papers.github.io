---
layout: publication
title: Neural Machine Translation With Source-side Latent Graph Parsing
authors: Hashimoto Kazuma, Tsuruoka Yoshimasa
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2017
bibkey: hashimoto2017neural
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1702.02265'}]
tags: [Model Architecture, Training Techniques, EMNLP, Datasets, Attention Mechanism]
---
This paper presents a novel neural machine translation model which jointly
learns translation and source-side latent graph representations of sentences.
Unlike existing pipelined approaches using syntactic parsers, our end-to-end
model learns a latent graph parser as part of the encoder of an attention-based
neural machine translation model, and thus the parser is optimized according to
the translation objective. In experiments, we first show that our model
compares favorably with state-of-the-art sequential and pipelined syntax-based
NMT models. We also show that the performance of our model can be further
improved by pre-training it with a small amount of treebank annotations. Our
final ensemble model significantly outperforms the previous best models on the
standard English-to-Japanese translation dataset.