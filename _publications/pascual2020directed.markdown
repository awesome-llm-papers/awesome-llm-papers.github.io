---
layout: publication
title: 'Directed Beam Search: Plug-and-play Lexically Constrained Language Generation'
authors: Pascual et al.
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2020
bibkey: pascual2020directed
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.15416'}]
tags: [Model Architecture, Training Techniques, ACL, Transformer, GPT]
---
Large pre-trained language models are capable of generating realistic text.
However, controlling these models so that the generated text satisfies lexical
constraints, i.e., contains specific words, is a challenging problem. Given
that state-of-the-art language models are too large to be trained from scratch
in a manageable time, it is desirable to control these models without
re-training them. Methods capable of doing this are called plug-and-play.
Recent plug-and-play methods have been successful in constraining small
bidirectional language models as well as forward models in tasks with a
restricted search space, e.g., machine translation. However, controlling large
transformer-based models to meet lexical constraints without re-training them
remains a challenge. In this work, we propose Directed Beam Search (DBS), a
plug-and-play method for lexically constrained language generation. Our method
can be applied to any language model, is easy to implement and can be used for
general language generation. In our experiments we use DBS to control GPT-2. We
demonstrate its performance on keyword-to-phrase generation and we obtain
comparable results as a state-of-the-art non-plug-and-play model for lexically
constrained story generation.