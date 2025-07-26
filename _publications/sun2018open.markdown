---
layout: publication
title: Open Domain Question Answering Using Early Fusion Of Knowledge Bases And Text
authors: Haitian Sun, Bhuwan Dhingra, Manzil Zaheer, Kathryn Mazaitis, Ruslan Salakhutdinov,
  William W. Cohen
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: sun2018open
citations: 400
additional_links: [{name: Code, url: 'https://github.com/OceanskySun/GraftNet'}, {
    name: Paper, url: 'https://arxiv.org/abs/1809.00782'}]
tags: ["EMNLP"]
short_authors: Sun et al.
---
Open Domain Question Answering (QA) is evolving from complex pipelined
systems to end-to-end deep neural networks. Specialized neural models have been
developed for extracting answers from either text alone or Knowledge Bases
(KBs) alone. In this paper we look at a more practical setting, namely QA over
the combination of a KB and entity-linked text, which is appropriate when an
incomplete KB is available with a large text corpus. Building on recent
advances in graph representation learning we propose a novel model, GRAFT-Net,
for extracting answers from a question-specific subgraph containing text and KB
entities and relations. We construct a suite of benchmark tasks for this
problem, varying the difficulty of questions, the amount of training data, and
KB completeness. We show that GRAFT-Net is competitive with the
state-of-the-art when tested using either KBs or text alone, and vastly
outperforms existing methods in the combined setting. Source code is available
at https://github.com/OceanskySun/GraftNet .