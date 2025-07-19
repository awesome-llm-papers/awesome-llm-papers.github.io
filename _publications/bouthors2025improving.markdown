---
layout: publication
title: Improving Retrieval-augmented Neural Machine Translation With Monolingual Data
authors: "Bouthors Maxime, Crego Josep, Yvon Fran\xE7ois"
conference: 'Proceedings of the 54th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2025
bibkey: bouthors2025improving
citations: 598
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.21747'}]
tags: [ACL, Model Architecture, RAG, Reinforcement Learning]
---
Conventional retrieval-augmented neural machine translation (RANMT) systems
leverage bilingual corpora, e.g., translation memories (TMs). Yet, in many
settings, in-domain monolingual target-side corpora are often available. This
work explores ways to take advantage of such resources by retrieving relevant
segments directly in the target language, based on a source-side query. For
this, we design improved cross-lingual retrieval systems, trained with both
sentence level and word-level matching objectives. In our experiments with two
RANMT architectures, we first demonstrate the benefits of such cross-lingual
objectives in a controlled setting, obtaining translation performances that
surpass standard TM-based models. We then showcase our method on a real-world
set-up, where the target monolingual resources far exceed the amount of
parallel data and observe large improvements of our new techniques, which
outperform both the baseline setting, and general-purpose cross-lingual
retrievers.