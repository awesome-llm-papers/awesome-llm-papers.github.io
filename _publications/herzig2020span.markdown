---
layout: publication
title: Span-based Semantic Parsing For Compositional Generalization
authors: Jonathan Herzig, Jonathan Berant
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: herzig2020span
citations: 64
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.06040'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Jonathan Herzig, Jonathan Berant
---
Despite the success of sequence-to-sequence (seq2seq) models in semantic
parsing, recent work has shown that they fail in compositional generalization,
i.e., the ability to generalize to new structures built of components observed
during training. In this work, we posit that a span-based parser should lead to
better compositional generalization. we propose SpanBasedSP, a parser that
predicts a span tree over an input utterance, explicitly encoding how partial
programs compose over spans in the input. SpanBasedSP extends Pasupat et al.
(2019) to be comparable to seq2seq models by (i) training from programs,
without access to gold trees, treating trees as latent variables, (ii) parsing
a class of non-projective trees through an extension to standard CKY. On
GeoQuery, SCAN and CLOSURE datasets, SpanBasedSP performs similarly to strong
seq2seq baselines on random splits, but dramatically improves performance
compared to baselines on splits that require compositional generalization: from
\\(61.0 \rightarrow 88.9\\) average accuracy.