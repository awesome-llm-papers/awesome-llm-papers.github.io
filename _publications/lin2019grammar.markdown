---
layout: publication
title: Grammar-based Neural Text-to-sql Generation
authors: Lin et al.
conference: Arxiv
year: 2019
bibkey: lin2019grammar
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.13326'}]
tags: [Datasets]
---
The sequence-to-sequence paradigm employed by neural text-to-SQL models
typically performs token-level decoding and does not consider generating SQL
hierarchically from a grammar. Grammar-based decoding has shown significant
improvements for other semantic parsing tasks, but SQL and other general
programming languages have complexities not present in logical formalisms that
make writing hierarchical grammars difficult. We introduce techniques to handle
these complexities, showing how to construct a schema-dependent grammar with
minimal over-generation. We analyze these techniques on ATIS and Spider, two
challenging text-to-SQL datasets, demonstrating that they yield 14--18%
relative reductions in error.