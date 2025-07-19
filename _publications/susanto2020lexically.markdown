---
layout: publication
title: Lexically Constrained Neural Machine Translation With Levenshtein Transformer
authors: Susanto Raymond Hendy, Chollampatt Shamil, Tan Liling
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: susanto2020lexically
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.12681'}]
tags: [Model Architecture, Training Techniques, ACL, Transformer, RAG, Datasets]
---
This paper proposes a simple and effective algorithm for incorporating
lexical constraints in neural machine translation. Previous work either
required re-training existing models with the lexical constraints or
incorporating them during beam search decoding with significantly higher
computational overheads. Leveraging the flexibility and speed of a recently
proposed Levenshtein Transformer model (Gu et al., 2019), our method injects
terminology constraints at inference time without any impact on decoding speed.
Our method does not require any modification to the training procedure and can
be easily applied at runtime with custom dictionaries. Experiments on
English-German WMT datasets show that our approach improves an unconstrained
baseline and previous approaches.