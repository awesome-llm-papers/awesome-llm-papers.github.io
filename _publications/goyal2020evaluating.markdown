---
layout: publication
title: Evaluating Factuality In Generation With Dependency-level Entailment
authors: Tanya Goyal, Greg Durrett
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: goyal2020evaluating
citations: 87
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.05478'}]
tags: ["EMNLP"]
short_authors: Tanya Goyal, Greg Durrett
---
Despite significant progress in text generation models, a serious limitation
is their tendency to produce text that is factually inconsistent with
information in the input. Recent work has studied whether textual entailment
systems can be used to identify factual errors; however, these sentence-level
entailment models are trained to solve a different problem than generation
filtering and they do not localize which part of a generation is non-factual.
In this paper, we propose a new formulation of entailment that decomposes it at
the level of dependency arcs. Rather than focusing on aggregate decisions, we
instead ask whether the semantic relationship manifested by individual
dependency arcs in the generated output is supported by the input. Human
judgments on this task are difficult to obtain; we therefore propose a method
to automatically create data based on existing entailment or paraphrase
corpora. Experiments show that our dependency arc entailment model trained on
this data can identify factual inconsistencies in paraphrasing and
summarization better than sentence-level methods or those based on question
generation, while additionally localizing the erroneous parts of the
generation.