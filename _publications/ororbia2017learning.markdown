---
layout: publication
title: Learning Simpler Language Models With The Differential State Framework
authors: Alexander G. Ororbia, Tomas Mikolov, David Reitter
conference: Neural Computation
year: 2017
bibkey: ororbia2017learning
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1703.08864'}]
tags: ["Model Architecture"]
short_authors: Alexander G. Ororbia, Tomas Mikolov, David Reitter
---
Learning useful information across long time lags is a critical and difficult
problem for temporal neural models in tasks such as language modeling. Existing
architectures that address the issue are often complex and costly to train. The
Differential State Framework (DSF) is a simple and high-performing design that
unifies previously introduced gated neural models. DSF models maintain
longer-term memory by learning to interpolate between a fast-changing
data-driven representation and a slowly changing, implicitly stable state. This
requires hardly any more parameters than a classical, simple recurrent network.
Within the DSF framework, a new architecture is presented, the Delta-RNN. In
language modeling at the word and character levels, the Delta-RNN outperforms
popular complex architectures, such as the Long Short Term Memory (LSTM) and
the Gated Recurrent Unit (GRU), and, when regularized, performs comparably to
several state-of-the-art baselines. At the subword level, the Delta-RNN's
performance is comparable to that of complex gated architectures.