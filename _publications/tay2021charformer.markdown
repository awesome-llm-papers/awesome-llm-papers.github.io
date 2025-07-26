---
layout: publication
title: 'Charformer: Fast Character Transformers Via Gradient-based Subword Tokenization'
authors: Yi Tay, Vinh Q. Tran, Sebastian Ruder, Jai Gupta, Hyung Won Chung, Dara Bahri,
  Zhen Qin, Simon Baumgartner, Cong Yu, Donald Metzler
conference: Arxiv
year: 2021
bibkey: tay2021charformer
citations: 70
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.12672'}]
tags: ["Model Architecture"]
short_authors: Tay et al.
---
State-of-the-art models in natural language processing rely on separate rigid
subword tokenization algorithms, which limit their generalization ability and
adaptation to new settings. In this paper, we propose a new model inductive
bias that learns a subword tokenization end-to-end as part of the model. To
this end, we introduce a soft gradient-based subword tokenization module (GBST)
that automatically learns latent subword representations from characters in a
data-driven fashion. Concretely, GBST enumerates candidate subword blocks and
learns to score them in a position-wise fashion using a block scoring network.
We additionally introduce Charformer, a deep Transformer model that integrates
GBST and operates on the byte level. Via extensive experiments on English GLUE,
multilingual, and noisy text datasets, we show that Charformer outperforms a
series of competitive byte-level baselines while generally performing on par
and sometimes outperforming subword-based models. Additionally, Charformer is
fast, improving the speed of both vanilla byte-level and subword-level
Transformers by 28%-100% while maintaining competitive quality. We believe this
work paves the way for highly performant token-free models that are trained
completely end-to-end.