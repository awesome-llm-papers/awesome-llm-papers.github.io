---
layout: publication
title: Transformer Feed-forward Layers Build Predictions By Promoting Concepts In
  The Vocabulary Space
authors: Mor Geva, Avi Caciularu, Kevin Ro Wang, Yoav Goldberg
conference: Proceedings of the 2022 Conference on Empirical Methods in Natural Language
  Processing
year: 2022
bibkey: geva2022transformer
citations: 70
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.14680'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Geva et al.
---
Transformer-based language models (LMs) are at the core of modern NLP, but
their internal prediction construction process is opaque and largely not
understood. In this work, we make a substantial step towards unveiling this
underlying prediction process, by reverse-engineering the operation of the
feed-forward network (FFN) layers, one of the building blocks of transformer
models. We view the token representation as a changing distribution over the
vocabulary, and the output from each FFN layer as an additive update to that
distribution. Then, we analyze the FFN updates in the vocabulary space, showing
that each update can be decomposed to sub-updates corresponding to single FFN
parameter vectors, each promoting concepts that are often human-interpretable.
We then leverage these findings for controlling LM predictions, where we reduce
the toxicity of GPT2 by almost 50%, and for improving computation efficiency
with a simple early exit rule, saving 20% of computation on average.