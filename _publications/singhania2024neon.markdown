---
layout: publication
title: 'Neon: News Entity-interaction Extraction For Enhanced Question Answering'
authors: Singhania et al.
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2024
bibkey: singhania2024neon
citations: 186
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.12449'}]
tags: [Merging, Tools, ACL, RAG, Reinforcement Learning]
---
Capturing fresh information in near real-time and using it to augment
existing large language models (LLMs) is essential to generate up-to-date,
grounded, and reliable output. This problem becomes particularly challenging
when LLMs are used for informational tasks in rapidly evolving fields, such as
Web search related to recent or unfolding events involving entities, where
generating temporally relevant responses requires access to up-to-the-hour news
sources. However, the information modeled by the parametric memory of LLMs is
often outdated, and Web results from prototypical retrieval systems may fail to
capture the latest relevant information and struggle to handle conflicting
reports in evolving news. To address this challenge, we present the NEON
framework, designed to extract emerging entity interactions -- such as events
or activities -- as described in news articles. NEON constructs an
entity-centric timestamped knowledge graph that captures such interactions,
thereby facilitating enhanced QA capabilities related to news events. Our
framework innovates by integrating open Information Extraction (openIE) style
tuples into LLMs to enable in-context retrieval-augmented generation. This
integration demonstrates substantial improvements in QA performance when
tackling temporal, entity-centric search queries. Through NEON, LLMs can
deliver more accurate, reliable, and up-to-date responses.