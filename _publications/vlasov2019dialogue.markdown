---
layout: publication
title: Dialogue Transformers
authors: Vladimir Vlasov, Johannes E. M. Mosig, Alan Nichol
conference: Arxiv
year: 2019
citations: 32
bibkey: vlasov2019dialogue
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.00486'}]
tags: [Transformer, Reinforcement Learning, Model Architecture, Attention Mechanism]
---
We introduce a dialogue policy based on a transformer architecture, where the
self-attention mechanism operates over the sequence of dialogue turns. Recent
work has used hierarchical recurrent neural networks to encode multiple
utterances in a dialogue context, but we argue that a pure self-attention
mechanism is more suitable. By default, an RNN assumes that every item in a
sequence is relevant for producing an encoding of the full sequence, but a
single conversation can consist of multiple overlapping discourse segments as
speakers interleave multiple topics. A transformer picks which turns to include
in its encoding of the current dialogue state, and is naturally suited to
selectively ignoring or attending to dialogue history. We compare the
performance of the Transformer Embedding Dialogue (TED) policy to an LSTM and
to the REDP, which was specifically designed to overcome this limitation of
RNNs.