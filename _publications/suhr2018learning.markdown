---
layout: publication
title: Learning To Map Context-dependent Sentences To Executable Formal Queries
authors: Alane Suhr, Srinivasan Iyer, Yoav Artzi
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 1
  (Long Papers)'
year: 2018
bibkey: suhr2018learning
citations: 95
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1804.06868'}]
tags: ["Applications", "In Context Learning", "Instruction Following", "Llm For Code", "Memory & Context", "NAACL"]
short_authors: Alane Suhr, Srinivasan Iyer, Yoav Artzi
---
We propose a context-dependent model to map utterances within an interaction
to executable formal queries. To incorporate interaction history, the model
maintains an interaction-level encoder that updates after each turn, and can
copy sub-sequences of previously predicted queries during generation. Our
approach combines implicit and explicit modeling of references between
utterances. We evaluate our model on the ATIS flight planning interactions, and
demonstrate the benefits of modeling context and explicit references.