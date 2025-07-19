---
layout: publication
title: Generating Analytic Specifications For Data Visualization From Natural Language
  Queries Using Large Language Models
authors: Sah et al.
conference: IEEE Transactions on Visualization and Computer Graphics
year: 2024
bibkey: sah2024generating
citations: 120
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2408.13391'}]
tags: [Interpretability And Explainability, GPT, Prompting, Evaluation, Model Architecture,
  Reinforcement Learning, Datasets]
---
Recently, large language models (LLMs) have shown great promise in
translating natural language (NL) queries into visualizations, but their
"black-box" nature often limits explainability and debuggability. In response,
we present a comprehensive text prompt that, given a tabular dataset and an NL
query about the dataset, generates an analytic specification including
(detected) data attributes, (inferred) analytic tasks, and (recommended)
visualizations. This specification captures key aspects of the query
translation process, affording both explainability and debuggability. For
instance, it provides mappings from the detected entities to the corresponding
phrases in the input query, as well as the specific visual design principles
that determined the visualization recommendations. Moreover, unlike prior
LLM-based approaches, our prompt supports conversational interaction and
ambiguity detection capabilities. In this paper, we detail the iterative
process of curating our prompt, present a preliminary performance evaluation
using GPT-4, and discuss the strengths and limitations of LLMs at various
stages of query translation. The prompt is open-source and integrated into
NL4DV, a popular Python-based natural language toolkit for visualization, which
can be accessed at https://nl4dv.github.io.