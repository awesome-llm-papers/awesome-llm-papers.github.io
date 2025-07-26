---
layout: publication
title: Coreference Resolution As Query-based Span Prediction
authors: Wei Wu, Fei Wang, Arianna Yuan, Fei Wu, Jiwei Li
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: wu2019coreference
citations: 155
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.01746'}]
tags: []
short_authors: Wu et al.
---
In this paper, we present an accurate and extensible approach for the
coreference resolution task. We formulate the problem as a span prediction
task, like in machine reading comprehension (MRC): A query is generated for
each candidate mention using its surrounding context, and a span prediction
module is employed to extract the text spans of the coreferences within the
document using the generated query. This formulation comes with the following
key advantages: (1) The span prediction strategy provides the flexibility of
retrieving mentions left out at the mention proposal stage; (2) In the MRC
framework, encoding the mention and its context explicitly in a query makes it
possible to have a deep and thorough examination of cues embedded in the
context of coreferent mentions; and (3) A plethora of existing MRC datasets can
be used for data augmentation to improve the model's generalization capability.
Experiments demonstrate significant performance boost over previous models,
with 87.5 (+2.5) F1 score on the GAP benchmark and 83.1 (+3.5) F1 score on the
CoNLL-2012 benchmark.