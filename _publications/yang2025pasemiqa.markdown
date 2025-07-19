---
layout: publication
title: 'Pasemiqa: Plan-assisted Agent For Question Answering On Semi-structured Data
  With Text And Relational Information'
authors: Yang et al.
conference: 'Proceedings of the 52nd Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2025
bibkey: yang2025pasemiqa
citations: 242
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.21087'}]
tags: [ACL, Agentic, RAG, Datasets, Reinforcement Learning]
---
Large language models (LLMs) have shown impressive abilities in answering
questions across various domains, but they often encounter hallucination issues
on questions that require professional and up-to-date knowledge. To address
this limitation, retrieval-augmented generation (RAG) techniques have been
proposed, which retrieve relevant information from external sources to inform
their responses. However, existing RAG methods typically focus on a single type
of external data, such as vectorized text database or knowledge graphs, and
cannot well handle real-world questions on semi-structured data containing both
text and relational information. To bridge this gap, we introduce PASemiQA, a
novel approach that jointly leverages text and relational information in
semi-structured data to answer questions. PASemiQA first generates a plan to
identify relevant text and relational information to answer the question in
semi-structured data, and then uses an LLM agent to traverse the
semi-structured data and extract necessary information. Our empirical results
demonstrate the effectiveness of PASemiQA across different semi-structured
datasets from various domains, showcasing its potential to improve the accuracy
and reliability of question answering systems on semi-structured data.