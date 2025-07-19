---
layout: publication
title: Syntactically Supervised Transformers For Faster Neural Machine Translation
authors: Akoury Nader, Krishna Kalpesh, Iyyer Mohit
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: akoury2019syntactically
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.02780'}]
tags: [Model Architecture, Training Techniques, ACL, Transformer, GPT, Datasets]
---
Standard decoders for neural machine translation autoregressively generate a
single target token per time step, which slows inference especially for long
outputs. While architectural advances such as the Transformer fully parallelize
the decoder computations at training time, inference still proceeds
sequentially. Recent developments in non- and semi- autoregressive decoding
produce multiple tokens per time step independently of the others, which
improves inference speed but deteriorates translation quality. In this work, we
propose the syntactically supervised Transformer (SynST), which first
autoregressively predicts a chunked parse tree before generating all of the
target tokens in one shot conditioned on the predicted parse. A series of
controlled experiments demonstrates that SynST decodes sentences ~ 5x faster
than the baseline autoregressive Transformer while achieving higher BLEU scores
than most competing methods on En-De and En-Fr datasets.