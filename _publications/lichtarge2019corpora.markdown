---
layout: publication
title: Corpora Generation For Grammatical Error Correction
authors: Jared Lichtarge, Chris Alberti, Shankar Kumar, Noam Shazeer, Niki Parmar,
  Simon Tong
conference: Proceedings of the 2019 Conference of the North
year: 2019
bibkey: lichtarge2019corpora
citations: 145
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.05780'}]
tags: ["Datasets", "Tools"]
short_authors: Lichtarge et al.
---
Grammatical Error Correction (GEC) has been recently modeled using the
sequence-to-sequence framework. However, unlike sequence transduction problems
such as machine translation, GEC suffers from the lack of plentiful parallel
data. We describe two approaches for generating large parallel datasets for GEC
using publicly available Wikipedia data. The first method extracts
source-target pairs from Wikipedia edit histories with minimal filtration
heuristics, while the second method introduces noise into Wikipedia sentences
via round-trip translation through bridge languages. Both strategies yield
similar sized parallel corpora containing around 4B tokens. We employ an
iterative decoding strategy that is tailored to the loosely supervised nature
of our constructed corpora. We demonstrate that neural GEC models trained using
either type of corpora give similar performance. Fine-tuning these models on
the Lang-8 corpus and ensembling allows us to surpass the state of the art on
both the CoNLL-2014 benchmark and the JFLEG task. We provide systematic
analysis that compares the two approaches to data generation and highlights the
effectiveness of ensembling.