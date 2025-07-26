---
layout: publication
title: 'XOR QA: Cross-lingual Open-retrieval Question Answering'
authors: Akari Asai, Jungo Kasai, Jonathan H. Clark, Kenton Lee, Eunsol Choi, Hannaneh
  Hajishirzi
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
bibkey: asai2020xor
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.11856'}]
tags: ["NAACL"]
short_authors: Asai et al.
---
Multilingual question answering tasks typically assume answers exist in the
same language as the question. Yet in practice, many languages face both
information scarcity -- where languages have few reference articles -- and
information asymmetry -- where questions reference concepts from other
cultures. This work extends open-retrieval question answering to a
cross-lingual setting enabling questions from one language to be answered via
answer content from another language. We construct a large-scale dataset built
on questions from TyDi QA lacking same-language answers. Our task formulation,
called Cross-lingual Open Retrieval Question Answering (XOR QA), includes 40k
information-seeking questions from across 7 diverse non-English languages.
Based on this dataset, we introduce three new tasks that involve cross-lingual
document retrieval using multi-lingual and English resources. We establish
baselines with state-of-the-art machine translation systems and cross-lingual
pretrained models. Experimental results suggest that XOR QA is a challenging
task that will facilitate the development of novel techniques for multilingual
question answering. Our data and code are available at
https://nlp.cs.washington.edu/xorqa.