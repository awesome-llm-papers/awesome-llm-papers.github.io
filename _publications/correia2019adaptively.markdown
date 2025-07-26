---
layout: publication
title: Adaptively Sparse Transformers
authors: "Gon\xE7alo M. Correia, Vlad Niculae, Andr\xE9 F. T. Martins"
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: correia2019adaptively
citations: 192
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.00015'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: "Gon\xE7alo M. Correia, Vlad Niculae, Andr\xE9 F. T. Martins"
---
Attention mechanisms have become ubiquitous in NLP. Recent architectures,
notably the Transformer, learn powerful context-aware word representations
through layered, multi-headed attention. The multiple heads learn diverse types
of word relationships. However, with standard softmax attention, all attention
heads are dense, assigning a non-zero weight to all context words. In this
work, we introduce the adaptively sparse Transformer, wherein attention heads
have flexible, context-dependent sparsity patterns. This sparsity is
accomplished by replacing softmax with \\(\alpha\\)-entmax: a differentiable
generalization of softmax that allows low-scoring words to receive precisely
zero weight. Moreover, we derive a method to automatically learn the \\(\alpha\\)
parameter -- which controls the shape and sparsity of \\(\alpha\\)-entmax --
allowing attention heads to choose between focused or spread-out behavior. Our
adaptively sparse Transformer improves interpretability and head diversity when
compared to softmax Transformers on machine translation datasets. Findings of
the quantitative and qualitative analysis of our approach include that heads in
different layers learn different sparsity preferences and tend to be more
diverse in their attention distributions than softmax Transformers.
Furthermore, at no cost in accuracy, sparsity in attention heads helps to
uncover different head specializations.