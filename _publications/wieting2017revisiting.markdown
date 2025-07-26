---
layout: publication
title: Revisiting Recurrent Networks For Paraphrastic Sentence Embeddings
authors: John Wieting, Kevin Gimpel
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2017
bibkey: wieting2017revisiting
citations: 74
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1705.00364'}]
tags: ["Model Architecture"]
short_authors: John Wieting, Kevin Gimpel
---
We consider the problem of learning general-purpose, paraphrastic sentence
embeddings, revisiting the setting of Wieting et al. (2016b). While they found
LSTM recurrent networks to underperform word averaging, we present several
developments that together produce the opposite conclusion. These include
training on sentence pairs rather than phrase pairs, averaging states to
represent sequences, and regularizing aggressively. These improve LSTMs in both
transfer learning and supervised settings. We also introduce a new recurrent
architecture, the Gated Recurrent Averaging Network, that is inspired by
averaging and LSTMs while outperforming them both. We analyze our learned
models, finding evidence of preferences for particular parts of speech and
dependency relations.