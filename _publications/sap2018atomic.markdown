---
layout: publication
title: 'ATOMIC: An Atlas Of Machine Commonsense For If-then Reasoning'
authors: Maarten Sap, Ronan Lebras, Emily Allaway, Chandra Bhagavatula, Nicholas Lourie,
  Hannah Rashkin, Brendan Roof, Noah A. Smith, Yejin Choi
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2019
bibkey: sap2018atomic
citations: 720
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1811.00146'}]
tags: ["AAAI", "Evaluation"]
short_authors: Sap et al.
---
We present ATOMIC, an atlas of everyday commonsense reasoning, organized
through 877k textual descriptions of inferential knowledge. Compared to
existing resources that center around taxonomic knowledge, ATOMIC focuses on
inferential knowledge organized as typed if-then relations with variables
(e.g., "if X pays Y a compliment, then Y will likely return the compliment").
We propose nine if-then relation types to distinguish causes vs. effects,
agents vs. themes, voluntary vs. involuntary events, and actions vs. mental
states. By generatively training on the rich inferential knowledge described in
ATOMIC, we show that neural models can acquire simple commonsense capabilities
and reason about previously unseen events. Experimental results demonstrate
that multitask models that incorporate the hierarchical structure of if-then
relation types lead to more accurate inference compared to models trained in
isolation, as measured by both automatic and human evaluation.