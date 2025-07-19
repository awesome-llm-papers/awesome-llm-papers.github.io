---
layout: publication
title: Constructing A Multi-hop QA Dataset For Comprehensive Evaluation Of Reasoning
  Steps
authors: Ho et al.
conference: Proceedings of the 28th International Conference on Computational Linguistics
year: 2020
bibkey: ho2020constructing
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2011.01060'}]
tags: [Interpretability And Explainability, RAG, COLING, Evaluation, Datasets]
---
A multi-hop question answering (QA) dataset aims to test reasoning and
inference skills by requiring a model to read multiple paragraphs to answer a
given question. However, current datasets do not provide a complete explanation
for the reasoning process from the question to the answer. Further, previous
studies revealed that many examples in existing multi-hop datasets do not
require multi-hop reasoning to answer a question. In this study, we present a
new multi-hop QA dataset, called 2WikiMultiHopQA, which uses structured and
unstructured data. In our dataset, we introduce the evidence information
containing a reasoning path for multi-hop questions. The evidence information
has two benefits: (i) providing a comprehensive explanation for predictions and
(ii) evaluating the reasoning skills of a model. We carefully design a pipeline
and a set of templates when generating a question-answer pair that guarantees
the multi-hop steps and the quality of the questions. We also exploit the
structured format in Wikidata and use logical rules to create questions that
are natural but still require multi-hop reasoning. Through experiments, we
demonstrate that our dataset is challenging for multi-hop models and it ensures
that multi-hop reasoning is required.