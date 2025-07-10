---
layout: publication
title: 'CBR-RAG: Case-based Reasoning For Retrieval Augmented Generation In Llms For
  Legal Question Answering'
authors: Nirmalie Wiratunga et al.
conference: Lecture Notes in Computer Science
year: 2024
citations: 32
bibkey: wiratunga2024cbr
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2404.04302'}]
tags: [Reinforcement Learning, RAG, Prompting, Evaluation]
---
Retrieval-Augmented Generation (RAG) enhances Large Language Model (LLM)
output by providing prior knowledge as context to input. This is beneficial for
knowledge-intensive and expert reliant tasks, including legal
question-answering, which require evidence to validate generated text outputs.
We highlight that Case-Based Reasoning (CBR) presents key opportunities to
structure retrieval as part of the RAG process in an LLM. We introduce CBR-RAG,
where CBR cycle's initial retrieval stage, its indexing vocabulary, and
similarity knowledge containers are used to enhance LLM queries with
contextually relevant cases. This integration augments the original LLM query,
providing a richer prompt. We present an evaluation of CBR-RAG, and examine
different representations (i.e. general and domain-specific embeddings) and
methods of comparison (i.e. inter, intra and hybrid similarity) on the task of
legal question-answering. Our results indicate that the context provided by
CBR's case reuse enforces similarity between relevant components of the
questions and the evidence base leading to significant improvements in the
quality of generated answers.