---
layout: publication
title: 'Semantic Captioning: Benchmark Dataset And Graph-aware Few-shot In-context
  Learning For Sql2text'
authors: Al-lawati Ali, Lucas Jason, Mitra Prasenjit
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: allawati2025semantic
citations: 121
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.03166'}]
tags: [RAG, Attention Mechanism, GPT, Alt, Prompting, Tools, CVPR, Evaluation, In
    Context Learning, Model Architecture, Few Shot, Security, Datasets, LLM For Code]
---
Large Language Models (LLMs) have demonstrated remarkable performance in
various NLP tasks, including semantic parsing, which translates natural
language into formal code representations. However, the reverse process,
translating code into natural language, termed semantic captioning, has
received less attention. This task is becoming increasingly important as LLMs
are integrated into platforms for code generation, security analysis, and
educational purposes. In this paper, we focus on the captioning of SQL query
(SQL2Text) to address the critical need for understanding and explaining SQL
queries in an era where LLM-generated code poses potential security risks. We
repurpose Text2SQL datasets for SQL2Text by introducing an iterative ICL prompt
using GPT-4o to generate multiple additional utterances, which enhances the
robustness of the datasets for the reverse task. We conduct our experiments
using in-context learning (ICL) based on different sample selection methods,
emphasizing smaller, more computationally efficient LLMs. Our findings
demonstrate that leveraging the inherent graph properties of SQL for ICL sample
selection significantly outperforms random selection by up to 39% on BLEU score
and provides better results than alternative methods. Dataset and codes are
published: https://github.com/aliwister/ast-icl.