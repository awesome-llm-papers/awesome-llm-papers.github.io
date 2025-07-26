---
layout: publication
title: Adaptive Attention Span In Transformers
authors: Sainbayar Sukhbaatar, Edouard Grave, Piotr Bojanowski, Armand Joulin
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: sukhbaatar2019adaptive
citations: 286
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.07799'}]
tags: ["Model Architecture"]
short_authors: Sukhbaatar et al.
---
We propose a novel self-attention mechanism that can learn its optimal
attention span. This allows us to extend significantly the maximum context size
used in Transformer, while maintaining control over their memory footprint and
computational time. We show the effectiveness of our approach on the task of
character level language modeling, where we achieve state-of-the-art
performances on text8 and enwiki8 by using a maximum context of 8k characters.