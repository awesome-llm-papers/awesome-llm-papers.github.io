---
layout: publication
title: 'Cascaded Beam Search: Plug-and-play Terminology-forcing For Neural Machine
  Translation'
authors: "Odermatt Fr\xE9d\xE9ric, Egressy B\xE9ni, Wattenhofer Roger"
conference: Proceedings of the First Workshop on Neural Machine Translation
year: 2023
bibkey: odermatt2023cascaded
citations: 183
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.14538'}]
tags: [Reinforcement Learning, Training Techniques, Merging]
---
This paper presents a plug-and-play approach for translation with terminology
constraints. Terminology constraints are an important aspect of many modern
translation pipelines. In both specialized domains and newly emerging domains
(such as the COVID-19 pandemic), accurate translation of technical terms is
crucial. Recent approaches often train models to copy terminologies from the
input into the output sentence by feeding the target terminology along with the
input. But this requires expensive training whenever the underlying language
model is changed or the system should specialize to a new domain. We propose
Cascade Beam Search, a plug-and-play terminology-forcing approach that requires
no training. Cascade Beam Search has two parts: 1) logit manipulation to
increase the probability of target terminologies and 2) a cascading beam setup
based on grid beam search, where beams are grouped by the number of
terminologies they contain. We evaluate the performance of our approach by
competing against the top submissions of the WMT21 terminology translation
task. Our plug-and-play approach performs on par with the winning submissions
without using a domain-specific language model and with no additional training.