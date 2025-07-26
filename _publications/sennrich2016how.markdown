---
layout: publication
title: How Grammatical Is Character-level Neural Machine Translation? Assessing MT
  Quality With Contrastive Translation Pairs
authors: Rico Sennrich
conference: 'Proceedings of the 15th Conference of the European Chapter of the Association
  for Computational Linguistics: Volume 2, Short Papers'
year: 2017
bibkey: sennrich2016how
citations: 91
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1612.04629'}]
tags: ["NAACL"]
short_authors: Rico Sennrich
---
Analysing translation quality in regards to specific linguistic phenomena has
historically been difficult and time-consuming. Neural machine translation has
the attractive property that it can produce scores for arbitrary translations,
and we propose a novel method to assess how well NMT systems model specific
linguistic phenomena such as agreement over long distances, the production of
novel words, and the faithful translation of polarity. The core idea is that we
measure whether a reference translation is more probable under a NMT model than
a contrastive translation which introduces a specific type of error. We present
LingEval97, a large-scale data set of 97000 contrastive translation pairs based
on the WMT English->German translation task, with errors automatically created
with simple rules. We report results for a number of systems, and find that
recently introduced character-level NMT systems perform better at
transliteration than models with byte-pair encoding (BPE) segmentation, but
perform more poorly at morphosyntactic agreement, and translating discontiguous
units of meaning.