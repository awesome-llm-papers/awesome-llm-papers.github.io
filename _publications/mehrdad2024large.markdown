---
layout: publication
title: Large Language Models For Relevance Judgment In Product Search
authors: Mehrdad et al.
conference: Proceedings of the 2023 ACM SIGIR International Conference on Theory of
  Information Retrieval
year: 2024
bibkey: mehrdad2024large
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.00247'}]
tags: [RAG, Prompting, SIGIR, Fine Tuning, Datasets]
---
High relevance of retrieved and re-ranked items to the search query is the
cornerstone of successful product search, yet measuring relevance of items to
queries is one of the most challenging tasks in product information retrieval,
and quality of product search is highly influenced by the precision and scale
of available relevance-labelled data. In this paper, we present an array of
techniques for leveraging Large Language Models (LLMs) for automating the
relevance judgment of query-item pairs (QIPs) at scale. Using a unique dataset
of multi-million QIPs, annotated by human evaluators, we test and optimize
hyper parameters for finetuning billion-parameter LLMs with and without Low
Rank Adaption (LoRA), as well as various modes of item attribute concatenation
and prompting in LLM finetuning, and consider trade offs in item attribute
inclusion for quality of relevance predictions. We demonstrate considerable
improvement over baselines of prior generations of LLMs, as well as
off-the-shelf models, towards relevance annotations on par with the human
relevance evaluators. Our findings have immediate implications for the growing
field of relevance judgment automation in product search.