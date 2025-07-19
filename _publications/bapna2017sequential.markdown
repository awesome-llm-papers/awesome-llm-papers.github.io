---
layout: publication
title: Sequential Dialogue Context Modeling For Spoken Language Understanding
authors: Bapna et al.
conference: Proceedings of the 18th Annual SIGdial Meeting on Discourse and Dialogue
year: 2017
bibkey: bapna2017sequential
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1705.03455'}]
tags: [Model Architecture, Datasets]
---
Spoken Language Understanding (SLU) is a key component of goal oriented
dialogue systems that would parse user utterances into semantic frame
representations. Traditionally SLU does not utilize the dialogue history beyond
the previous system turn and contextual ambiguities are resolved by the
downstream components. In this paper, we explore novel approaches for modeling
dialogue context in a recurrent neural network (RNN) based language
understanding system. We propose the Sequential Dialogue Encoder Network, that
allows encoding context from the dialogue history in chronological order. We
compare the performance of our proposed architecture with two context models,
one that uses just the previous turn context and another that encodes dialogue
context in a memory network, but loses the order of utterances in the dialogue
history. Experiments with a multi-domain dialogue dataset demonstrate that the
proposed architecture results in reduced semantic frame error rates.