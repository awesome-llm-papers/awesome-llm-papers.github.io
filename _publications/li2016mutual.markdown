---
layout: publication
title: Mutual Information And Diverse Decoding Improve Neural Machine Translation
authors: Jiwei Li, Dan Jurafsky
conference: Arxiv
year: 2016
bibkey: li2016mutual
citations: 99
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1601.00372'}]
tags: ["Model Architecture"]
short_authors: Jiwei Li, Dan Jurafsky
---
Sequence-to-sequence neural translation models learn semantic and syntactic
relations between sentence pairs by optimizing the likelihood of the target
given the source, i.e., \\(p(y|x)\\), an objective that ignores other potentially
useful sources of information. We introduce an alternative objective function
for neural MT that maximizes the mutual information between the source and
target sentences, modeling the bi-directional dependency of sources and
targets. We implement the model with a simple re-ranking method, and also
introduce a decoding algorithm that increases diversity in the N-best list
produced by the first pass. Applied to the WMT German/English and
French/English tasks, the proposed models offers a consistent performance boost
on both standard LSTM and attention-based neural MT architectures.