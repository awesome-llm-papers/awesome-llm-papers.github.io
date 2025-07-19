---
layout: publication
title: 'Ukp-athene: Multi-sentence Textual Entailment For Claim Verification'
authors: Hanselowski et al.
conference: Proceedings of the First Workshop on Fact Extraction and VERification
  (FEVER)
year: 2018
bibkey: hanselowski2018ukp
citations: 184
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.01479'}]
tags: [Model Architecture, Reinforcement Learning, Datasets]
---
The Fact Extraction and VERification (FEVER) shared task was launched to
support the development of systems able to verify claims by extracting
supporting or refuting facts from raw text. The shared task organizers provide
a large-scale dataset for the consecutive steps involved in claim verification,
in particular, document retrieval, fact extraction, and claim classification.
In this paper, we present our claim verification pipeline approach, which,
according to the preliminary results, scored third in the shared task, out of
23 competing systems. For the document retrieval, we implemented a new entity
linking approach. In order to be able to rank candidate facts and classify a
claim on the basis of several selected facts, we introduce two extensions to
the Enhanced LSTM (ESIM).