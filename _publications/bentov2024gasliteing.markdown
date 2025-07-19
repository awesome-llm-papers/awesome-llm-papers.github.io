---
layout: publication
title: 'Gasliteing The Retrieval: Exploring Vulnerabilities In Dense Embedding-based
  Search'
authors: Ben-tov Matan, Sharif Mahmood
conference: Proceedings of the 26th ACM SIGKDD International Conference on Knowledge
  Discovery &amp; Data Mining
year: 2024
bibkey: bentov2024gasliteing
citations: 205
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.20953'}]
tags: [RAG, Efficiency And Optimization, Reinforcement Learning, Security, Datasets,
  KDD]
---
Dense embedding-based text retrieval\\(\unicode\{x2013\}\\)retrieval of relevant
passages from corpora via deep learning encodings\\(\unicode\{x2013\}\\)has emerged
as a powerful method attaining state-of-the-art search results and popularizing
the use of Retrieval Augmented Generation (RAG). Still, like other search
methods, embedding-based retrieval may be susceptible to search-engine
optimization (SEO) attacks, where adversaries promote malicious content by
introducing adversarial passages to corpora. To faithfully assess and gain
insights into the susceptibility of such systems to SEO, this work proposes the
GASLITE attack, a mathematically principled gradient-based search method for
generating adversarial passages without relying on the corpus content or
modifying the model. Notably, GASLITE's passages (1) carry adversary-chosen
information while (2) achieving high retrieval ranking for a selected query
distribution when inserted to corpora. We use GASLITE to extensively evaluate
retrievers' robustness, testing nine advanced models under varied threat
models, while focusing on realistic adversaries targeting queries on a specific
concept (e.g., a public figure). We found GASLITE consistently outperformed
baselines by \\(\geq\\)140% success rate, in all settings. Particularly,
adversaries using GASLITE require minimal effort to manipulate search
results\\(\unicode\{x2013\}\\)by injecting a negligible amount of adversarial
passages (\\(\leq\\)0.0001% of the corpus), they could make them visible in the
top-10 results for 61-100% of unseen concept-specific queries against most
evaluated models. Inspecting variance in retrievers' robustness, we identify
key factors that may contribute to models' susceptibility to SEO, including
specific properties in the embedding space's geometry.