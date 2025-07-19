---
layout: publication
title: 'Hover: A Dataset For Many-hop Fact Extraction And Claim Verification'
authors: Jiang et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: jiang2020hover
citations: 77
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2011.03088'}]
tags: [Evaluation, ACL, EMNLP, RAG, Datasets, Reinforcement Learning]
---
We introduce HoVer (HOppy VERification), a dataset for many-hop evidence
extraction and fact verification. It challenges models to extract facts from
several Wikipedia articles that are relevant to a claim and classify whether
the claim is Supported or Not-Supported by the facts. In HoVer, the claims
require evidence to be extracted from as many as four English Wikipedia
articles and embody reasoning graphs of diverse shapes. Moreover, most of the
3/4-hop claims are written in multiple sentences, which adds to the complexity
of understanding long-range dependency relations such as coreference. We show
that the performance of an existing state-of-the-art semantic-matching model
degrades significantly on our dataset as the number of reasoning hops
increases, hence demonstrating the necessity of many-hop reasoning to achieve
strong results. We hope that the introduction of this challenging dataset and
the accompanying evaluation task will encourage research in many-hop fact
retrieval and information verification. We make the HoVer dataset publicly
available at https://hover-nlp.github.io