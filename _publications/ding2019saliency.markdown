---
layout: publication
title: Saliency-driven Word Alignment Interpretation For Neural Machine Translation
authors: Shuoyang Ding, Hainan Xu, Philipp Koehn
conference: 'Proceedings of the Fourth Conference on Machine Translation (Volume 1:
  Research Papers)'
year: 2019
bibkey: ding2019saliency
citations: 60
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.10282'}]
tags: ["Model Architecture"]
short_authors: Shuoyang Ding, Hainan Xu, Philipp Koehn
---
Despite their original goal to jointly learn to align and translate, Neural
Machine Translation (NMT) models, especially Transformer, are often perceived
as not learning interpretable word alignments. In this paper, we show that NMT
models do learn interpretable word alignments, which could only be revealed
with proper interpretation methods. We propose a series of such methods that
are model-agnostic, are able to be applied either offline or online, and do not
require parameter update or architectural change. We show that under the force
decoding setup, the alignments induced by our interpretation method are of
better quality than fast-align for some systems, and when performing free
decoding, they agree well with the alignments induced by automatic alignment
tools.