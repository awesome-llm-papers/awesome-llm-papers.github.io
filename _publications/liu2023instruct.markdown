---
layout: publication
title: 'Instruct-sctg: Guiding Sequential Controlled Text Generation Through Instructions'
authors: Liu et al.
conference: Lecture Notes in Computer Science
year: 2023
bibkey: liu2023instruct
citations: 76
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.12299'}]
tags: [Language Modeling, Tools, Evaluation, Datasets]
---
Instruction-tuned large language models have shown remarkable performance in
aligning generated text with user intentions across various tasks. However,
maintaining human-like discourse structure in the generated text remains a
challenging research question. In this paper, we propose Instruct-SCTG, a
flexible and effective sequential framework that harnesses instruction-tuned
language models to generate structurally coherent text in both fine-tuned and
zero-shot setups. Our framework generates articles in a section-by-section
manner, aligned with the desired human structure using natural language
instructions. Furthermore, we introduce a new automatic metric that measures
discourse divergence in a fuzzy manner. Extensive experiments on three datasets
from representative domains of news and recipes demonstrate the
state-of-the-art performance of our framework in imposing discourse structure
during text generation, as verified by both automatic and human evaluation. Our
code will be available on Github.