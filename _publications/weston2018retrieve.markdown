---
layout: publication
title: 'Retrieve And Refine: Improved Sequence Generation Models For Dialogue'
authors: Jason Weston, Emily Dinan, Alexander H. Miller
conference: 'Proceedings of the 2018 EMNLP Workshop SCAI: The 2nd International Workshop
  on Search-Oriented Conversational AI'
year: 2018
bibkey: weston2018retrieve
citations: 186
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.04776'}]
tags: ["Dialogue & Multi Turn", "EMNLP"]
short_authors: Jason Weston, Emily Dinan, Alexander H. Miller
---
Sequence generation models for dialogue are known to have several problems:
they tend to produce short, generic sentences that are uninformative and
unengaging. Retrieval models on the other hand can surface interesting
responses, but are restricted to the given retrieval set leading to erroneous
replies that cannot be tuned to the specific context. In this work we develop a
model that combines the two approaches to avoid both their deficiencies: first
retrieve a response and then refine it -- the final sequence generator treating
the retrieval as additional context. We show on the recent CONVAI2 challenge
task our approach produces responses superior to both standard retrieval and
generation models in human evaluations.