---
layout: publication
title: 'Re2g: Retrieve, Rerank, Generate'
authors: Michael Glass et al.
conference: 'Proceedings of the 2022 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2022
citations: 27
bibkey: glass2022generate
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2207.06300'}, {name: Code,
    url: 'https://github.com/IBM/kgi-slot-filling/tree/re2g'}]
tags: [Has Code, Model Architecture, Distillation, Transformer, RAG, Efficiency and
    Optimization, GPT, Evaluation, Merging]
---
As demonstrated by GPT-3 and T5, transformers grow in capability as parameter
spaces become larger and larger. However, for tasks that require a large amount
of knowledge, non-parametric memory allows models to grow dramatically with a
sub-linear increase in computational cost and GPU memory requirements. Recent
models such as RAG and REALM have introduced retrieval into conditional
generation. These models incorporate neural initial retrieval from a corpus of
passages. We build on this line of research, proposing Re2G, which combines
both neural initial retrieval and reranking into a BART-based
sequence-to-sequence generation. Our reranking approach also permits merging
retrieval results from sources with incomparable scores, enabling an ensemble
of BM25 and neural initial retrieval. To train our system end-to-end, we
introduce a novel variation of knowledge distillation to train the initial
retrieval, reranker, and generation using only ground truth on the target
sequence output. We find large gains in four diverse tasks: zero-shot slot
filling, question answering, fact-checking, and dialog, with relative gains of
9% to 34% over the previous state-of-the-art on the KILT leaderboard. We make
our code available as open source at
https://github.com/IBM/kgi-slot-filling/tree/re2g.