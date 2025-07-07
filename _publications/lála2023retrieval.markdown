---
layout: publication
title: 'Paperqa: Retrieval-augmented Generative Agent For Scientific Research'
authors: "Jakub L\xE1la et al."
conference: Arxiv
year: 2023
citations: 21
bibkey: "l\xE1la2023retrieval"
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.07559'}]
tags: [RAG, Interpretability and Explainability, Agentic]
---
Large Language Models (LLMs) generalize well across language tasks, but
suffer from hallucinations and uninterpretability, making it difficult to
assess their accuracy without ground-truth. Retrieval-Augmented Generation
(RAG) models have been proposed to reduce hallucinations and provide provenance
for how an answer was generated. Applying such models to the scientific
literature may enable large-scale, systematic processing of scientific
knowledge. We present PaperQA, a RAG agent for answering questions over the
scientific literature. PaperQA is an agent that performs information retrieval
across full-text scientific articles, assesses the relevance of sources and
passages, and uses RAG to provide answers. Viewing this agent as a question
answering model, we find it exceeds performance of existing LLMs and LLM agents
on current science QA benchmarks. To push the field closer to how humans
perform research on scientific literature, we also introduce LitQA, a more
complex benchmark that requires retrieval and synthesis of information from
full-text scientific papers across the literature. Finally, we demonstrate
PaperQA's matches expert human researchers on LitQA.