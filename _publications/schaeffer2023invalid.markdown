---
layout: publication
title: 'Invalid Logic, Equivalent Gains: The Bizarreness Of Reasoning In Language
  Model Prompting'
authors: Schaeffer et al.
conference: 'Proceedings of the 61st Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2023
bibkey: schaeffer2023invalid
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.10573'}]
tags: [Datasets, Prompting, ACL, Evaluation]
---
Language models can be prompted to reason through problems in a manner that
significantly improves performance. However, \textit\{why\} such prompting
improves performance is unclear. Recent work showed that using logically
\textit\{invalid\} Chain-of-Thought (CoT) prompting improves performance almost
as much as logically \textit\{valid\} CoT prompting, and that editing CoT prompts
to replace problem-specific information with abstract information or
out-of-distribution information typically doesn't harm performance. Critics
have responded that these findings are based on too few and too easily solved
tasks to draw meaningful conclusions. To resolve this dispute, we test whether
logically invalid CoT prompts offer the same level of performance gains as
logically valid prompts on the hardest tasks in the BIG-Bench benchmark, termed
BIG-Bench Hard (BBH). We find that the logically \textit\{invalid\} reasoning
prompts do indeed achieve similar performance gains on BBH tasks as logically
valid reasoning prompts. We also discover that some CoT prompts used by
previous works contain logical errors. This suggests that covariates beyond
logically valid reasoning are responsible for performance improvements.