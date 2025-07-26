---
layout: publication
title: Semantic Parsing For Task Oriented Dialog Using Hierarchical Representations
authors: Sonal Gupta, Rushin Shah, Mrinal Mohit, Anuj Kumar, Mike Lewis
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: gupta2018semantic
citations: 189
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1810.07942'}]
tags: ["EMNLP"]
short_authors: Gupta et al.
---
Task oriented dialog systems typically first parse user utterances to
semantic frames comprised of intents and slots. Previous work on task oriented
intent and slot-filling work has been restricted to one intent per query and
one slot label per token, and thus cannot model complex compositional requests.
Alternative semantic parsing systems have represented queries as logical forms,
but these are challenging to annotate and parse. We propose a hierarchical
annotation scheme for semantic parsing that allows the representation of
compositional queries, and can be efficiently and accurately parsed by standard
constituency parsing models. We release a dataset of 44k annotated queries
(fb.me/semanticparsingdialog), and show that parsing models outperform
sequence-to-sequence approaches on this dataset.