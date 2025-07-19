---
layout: publication
title: 'AIR: Complex Instruction Generation Via Automatic Iterative Refinement'
authors: Liu et al.
conference: Europhysics Letters (EPL)
year: 2025
bibkey: liu2025air
citations: 101
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.17787'}]
tags: [RAG, Tools, Datasets]
---
With the development of large language models, their ability to follow simple
instructions has significantly improved. However, adhering to complex
instructions remains a major challenge. Current approaches to generating
complex instructions are often irrelevant to the current instruction
requirements or suffer from limited scalability and diversity. Moreover,
methods such as back-translation, while effective for simple instruction
generation, fail to leverage the rich contents and structures in large web
corpora. In this paper, we propose a novel automatic iterative refinement
framework to generate complex instructions with constraints, which not only
better reflects the requirements of real scenarios but also significantly
enhances LLMs' ability to follow complex instructions. The AIR framework
consists of two stages: (1)Generate an initial instruction from a document;
(2)Iteratively refine instructions with LLM-as-judge guidance by comparing the
model's output with the document to incorporate valuable constraints. Finally,
we construct the AIR-10K dataset with 10K complex instructions and demonstrate
that instructions generated with our approach significantly improve the model's
ability to follow complex instructions, outperforming existing methods for
instruction generation.