---
layout: publication
title: Retrieval Augmentation Of Large Language Models For Lay Language Generation
authors: Yue Guo, Wei Qiu, Gondy Leroy, Sheng Wang, Trevor Cohen
conference: Arxiv
year: 2022
citations: 25
bibkey: guo2022retrieval
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.03818'}, {name: Code,
    url: 'https://github.com/LinguisticAnomalies/pls_retrieval'}]
tags: [Transformer, RAG, Interpretability and Explainability, Has Code, Survey Paper,
  Model Architecture]
---
Recent lay language generation systems have used Transformer models trained
on a parallel corpus to increase health information accessibility. However, the
applicability of these models is constrained by the limited size and topical
breadth of available corpora. We introduce CELLS, the largest (63k pairs) and
broadest-ranging (12 journals) parallel corpus for lay language generation. The
abstract and the corresponding lay language summary are written by domain
experts, assuring the quality of our dataset. Furthermore, qualitative
evaluation of expert-authored plain language summaries has revealed background
explanation as a key strategy to increase accessibility. Such explanation is
challenging for neural models to generate because it goes beyond simplification
by adding content absent from the source. We derive two specialized paired
corpora from CELLS to address key challenges in lay language generation:
generating background explanations and simplifying the original abstract. We
adopt retrieval-augmented models as an intuitive fit for the task of background
explanation generation, and show improvements in summary quality and simplicity
while maintaining factual correctness. Taken together, this work presents the
first comprehensive study of background explanation for lay language
generation, paving the path for disseminating scientific knowledge to a broader
audience. CELLS is publicly available at:
https://github.com/LinguisticAnomalies/pls_retrieval.