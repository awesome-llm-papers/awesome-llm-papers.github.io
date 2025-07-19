---
layout: publication
title: Learning To Remember Translation History With A Continuous Cache
authors: Tu et al.
conference: Transactions of the Association for Computational Linguistics
year: 2017
bibkey: tu2017learning
citations: 186
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1711.09367'}]
tags: [TACL, Reinforcement Learning, ACL]
---
Existing neural machine translation (NMT) models generally translate
sentences in isolation, missing the opportunity to take advantage of
document-level information. In this work, we propose to augment NMT models with
a very light-weight cache-like memory network, which stores recent hidden
representations as translation history. The probability distribution over
generated words is updated online depending on the translation history
retrieved from the memory, endowing NMT models with the capability to
dynamically adapt over time. Experiments on multiple domains with different
topics and styles show the effectiveness of the proposed approach with
negligible impact on the computational cost.