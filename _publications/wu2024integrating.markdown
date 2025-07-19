---
layout: publication
title: Integrating Knowledge Retrieval And Large Language Models For Clinical Report
  Correction
authors: Wu et al.
conference: Nature
year: 2024
bibkey: wu2024integrating
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.15045'}]
tags: [Interpretability And Explainability, RAG, Tools, Evaluation, Reinforcement
    Learning, Datasets]
---
This study proposes an approach for error correction in radiology reports,
leveraging large language models (LLMs) and retrieval-augmented generation
(RAG) techniques. The proposed framework employs a novel internal+external
retrieval mechanism to extract relevant medical entities and relations from the
report of interest and an external knowledge source. A three-stage inference
process is introduced, decomposing the task into error detection, localization,
and correction subtasks, which enhances the explainability and performance of
the system. The effectiveness of the approach is evaluated using a benchmark
dataset created by corrupting real-world radiology reports with realistic
errors, guided by domain experts. Experimental results demonstrate the benefits
of the proposed methods, with the combination of internal and external
retrieval significantly improving the accuracy of error detection,
localization, and correction across various state-of-the-art LLMs. The findings
contribute to the development of more robust and reliable error correction
systems for clinical documentation.