---
layout: publication
title: Constrained Decoding For Neural NLG From Compositional Representations In Task-oriented
  Dialogue
authors: Anusha Balakrishnan, Jinfeng Rao, Kartikeya Upasani, Michael White, Rajen
  Subba
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: balakrishnan2019constrained
citations: 77
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.07220'}]
tags: ["Datasets"]
short_authors: Balakrishnan et al.
---
Generating fluent natural language responses from structured semantic
representations is a critical step in task-oriented conversational systems.
Avenues like the E2E NLG Challenge have encouraged the development of neural
approaches, particularly sequence-to-sequence (Seq2Seq) models for this
problem. The semantic representations used, however, are often underspecified,
which places a higher burden on the generation model for sentence planning, and
also limits the extent to which generated responses can be controlled in a live
system. In this paper, we (1) propose using tree-structured semantic
representations, like those used in traditional rule-based NLG systems, for
better discourse-level structuring and sentence-level planning; (2) introduce a
challenging dataset using this representation for the weather domain; (3)
introduce a constrained decoding approach for Seq2Seq models that leverages
this representation to improve semantic correctness; and (4) demonstrate
promising results on our dataset and the E2E dataset.