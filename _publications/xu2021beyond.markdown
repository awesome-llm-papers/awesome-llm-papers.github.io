---
layout: publication
title: 'Beyond Goldfish Memory: Long-term Open-domain Conversation'
authors: Jing Xu, Arthur Szlam, Jason Weston
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: xu2021beyond
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2107.07567'}]
tags: ["Datasets", "RAG"]
short_authors: Jing Xu, Arthur Szlam, Jason Weston
---
Despite recent improvements in open-domain dialogue models, state of the art
models are trained and evaluated on short conversations with little context. In
contrast, the long-term conversation setting has hardly been studied. In this
work we collect and release a human-human dataset consisting of multiple chat
sessions whereby the speaking partners learn about each other's interests and
discuss the things they have learnt from past sessions. We show how existing
models trained on existing datasets perform poorly in this long-term
conversation setting in both automatic and human evaluations, and we study
long-context models that can perform much better. In particular, we find
retrieval-augmented methods and methods with an ability to summarize and recall
previous conversations outperform the standard encoder-decoder architectures
currently considered state of the art.