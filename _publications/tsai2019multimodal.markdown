---
layout: publication
title: Multimodal Transformer For Unaligned Multimodal Language Sequences
authors: Yao-hung Hubert Tsai, Shaojie Bai, Paul Pu Liang, J. Zico Kolter, Louis-philippe
  Morency, Ruslan Salakhutdinov
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: tsai2019multimodal
citations: 1063
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.00295'}]
tags: ["Model Architecture"]
short_authors: Tsai et al.
---
Human language is often multimodal, which comprehends a mixture of natural
language, facial gestures, and acoustic behaviors. However, two major
challenges in modeling such multimodal human language time-series data exist:
1) inherent data non-alignment due to variable sampling rates for the sequences
from each modality; and 2) long-range dependencies between elements across
modalities. In this paper, we introduce the Multimodal Transformer (MulT) to
generically address the above issues in an end-to-end manner without explicitly
aligning the data. At the heart of our model is the directional pairwise
crossmodal attention, which attends to interactions between multimodal
sequences across distinct time steps and latently adapt streams from one
modality to another. Comprehensive experiments on both aligned and non-aligned
multimodal time-series show that our model outperforms state-of-the-art methods
by a large margin. In addition, empirical analysis suggests that correlated
crossmodal signals are able to be captured by the proposed crossmodal attention
mechanism in MulT.