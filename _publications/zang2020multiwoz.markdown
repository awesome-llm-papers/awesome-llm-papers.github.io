---
layout: publication
title: 'Multiwoz 2.2 : A Dialogue Dataset With Additional Annotation Corrections And
  State Tracking Baselines'
authors: Xiaoxue Zang, Abhinav Rastogi, Srinivas Sunkara, Raghav Gupta, Jianguo Zhang,
  Jindong Chen
conference: Proceedings of the 2nd Workshop on Natural Language Processing for Conversational
  AI
year: 2020
bibkey: zang2020multiwoz
citations: 166
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2007.12720'}]
tags: ["Datasets"]
short_authors: Zang et al.
---
MultiWOZ is a well-known task-oriented dialogue dataset containing over
10,000 annotated dialogues spanning 8 domains. It is extensively used as a
benchmark for dialogue state tracking. However, recent works have reported
presence of substantial noise in the dialogue state annotations. MultiWOZ 2.1
identified and fixed many of these erroneous annotations and user utterances,
resulting in an improved version of this dataset. This work introduces MultiWOZ
2.2, which is a yet another improved version of this dataset. Firstly, we
identify and fix dialogue state annotation errors across 17.3% of the
utterances on top of MultiWOZ 2.1. Secondly, we redefine the ontology by
disallowing vocabularies of slots with a large number of possible values (e.g.,
restaurant name, time of booking). In addition, we introduce slot span
annotations for these slots to standardize them across recent models, which
previously used custom string matching heuristics to generate them. We also
benchmark a few state of the art dialogue state tracking models on the
corrected dataset to facilitate comparison for future work. In the end, we
discuss best practices for dialogue data collection that can help avoid
annotation errors.