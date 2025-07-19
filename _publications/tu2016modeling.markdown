---
layout: publication
title: Modeling Coverage For Neural Machine Translation
authors: Tu et al.
conference: 'Proceedings of the 54th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2016
bibkey: tu2016modeling
citations: 676
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1601.04811'}]
tags: [Model Architecture, ACL, Transformer, RAG, Attention Mechanism]
---
Attention mechanism has enhanced state-of-the-art Neural Machine Translation
(NMT) by jointly learning to align and translate. It tends to ignore past
alignment information, however, which often leads to over-translation and
under-translation. To address this problem, we propose coverage-based NMT in
this paper. We maintain a coverage vector to keep track of the attention
history. The coverage vector is fed to the attention model to help adjust
future attention, which lets NMT system to consider more about untranslated
source words. Experiments show that the proposed approach significantly
improves both translation quality and alignment quality over standard
attention-based NMT.