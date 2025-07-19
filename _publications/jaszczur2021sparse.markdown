---
layout: publication
title: Sparse Is Enough In Scaling Transformers
authors: Jaszczur et al.
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2021
bibkey: jaszczur2021sparse
citations: 77
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2111.12763'}]
tags: [RAG, EMNLP, Attention Mechanism, Transformer, Model Architecture]
---
Large Transformer models yield impressive results on many tasks, but are
expensive to train, or even fine-tune, and so slow at decoding that their use
and study becomes out of reach. We address this problem by leveraging sparsity.
We study sparse variants for all layers in the Transformer and propose Scaling
Transformers, a family of next generation Transformer models that use sparse
layers to scale efficiently and perform unbatched decoding much faster than the
standard Transformer as we scale up the model size. Surprisingly, the sparse
layers are enough to obtain the same perplexity as the standard Transformer
with the same number of parameters. We also integrate with prior sparsity
approaches to attention and enable fast inference on long sequences even with
limited memory. This results in performance competitive to the state-of-the-art
on long text summarization.