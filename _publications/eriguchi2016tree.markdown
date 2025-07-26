---
layout: publication
title: Tree-to-sequence Attentional Neural Machine Translation
authors: Akiko Eriguchi, Kazuma Hashimoto, Yoshimasa Tsuruoka
conference: 'Proceedings of the 54th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2016
bibkey: eriguchi2016tree
citations: 255
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1603.06075'}]
tags: ["Model Architecture"]
short_authors: Akiko Eriguchi, Kazuma Hashimoto, Yoshimasa Tsuruoka
---
Most of the existing Neural Machine Translation (NMT) models focus on the
conversion of sequential data and do not directly use syntactic information. We
propose a novel end-to-end syntactic NMT model, extending a
sequence-to-sequence model with the source-side phrase structure. Our model has
an attention mechanism that enables the decoder to generate a translated word
while softly aligning it with phrases as well as words of the source sentence.
Experimental results on the WAT'15 English-to-Japanese dataset demonstrate that
our proposed model considerably outperforms sequence-to-sequence attentional
NMT models and compares favorably with the state-of-the-art tree-to-string SMT
system.