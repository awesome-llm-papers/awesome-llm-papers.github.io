---
layout: publication
title: Tree-structured Attention With Hierarchical Accumulation
authors: Nguyen et al.
conference: Arxiv
year: 2020
bibkey: nguyen2020tree
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2002.08046'}]
tags: [Attention Mechanism, Transformer, Model Architecture, SLT]
---
Incorporating hierarchical structures like constituency trees has been shown
to be effective for various natural language processing (NLP) tasks. However,
it is evident that state-of-the-art (SOTA) sequence-based models like the
Transformer struggle to encode such structures inherently. On the other hand,
dedicated models like the Tree-LSTM, while explicitly modeling hierarchical
structures, do not perform as efficiently as the Transformer. In this paper, we
attempt to bridge this gap with "Hierarchical Accumulation" to encode parse
tree structures into self-attention at constant time complexity. Our approach
outperforms SOTA methods in four IWSLT translation tasks and the WMT'14
English-German translation task. It also yields improvements over Transformer
and Tree-LSTM on three text classification tasks. We further demonstrate that
using hierarchical priors can compensate for data shortage, and that our model
prefers phrase-level attentions over token-level attentions.