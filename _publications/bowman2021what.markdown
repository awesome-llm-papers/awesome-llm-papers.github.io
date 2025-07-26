---
layout: publication
title: What Will It Take To Fix Benchmarking In Natural Language Understanding?
authors: Samuel R. Bowman, George E. Dahl
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
bibkey: bowman2021what
citations: 86
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.02145'}]
tags: ["Evaluation", "NAACL"]
short_authors: Samuel R. Bowman, George E. Dahl
---
Evaluation for many natural language understanding (NLU) tasks is broken:
Unreliable and biased systems score so highly on standard benchmarks that there
is little room for researchers who develop better systems to demonstrate their
improvements. The recent trend to abandon IID benchmarks in favor of
adversarially-constructed, out-of-distribution test sets ensures that current
models will perform poorly, but ultimately only obscures the abilities that we
want our benchmarks to measure. In this position paper, we lay out four
criteria that we argue NLU benchmarks should meet. We argue most current
benchmarks fail at these criteria, and that adversarial data collection does
not meaningfully address the causes of these failures. Instead, restoring a
healthy evaluation ecosystem will require significant progress in the design of
benchmark datasets, the reliability with which they are annotated, their size,
and the ways they handle social bias.