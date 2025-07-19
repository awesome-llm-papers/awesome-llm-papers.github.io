---
layout: publication
title: Fusing Context Into Knowledge Graph For Commonsense Question Answering
authors: Xu et al.
conference: 'Findings of the Association for Computational Linguistics: ACL-IJCNLP
  2021'
year: 2020
bibkey: xu2020fusing
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.04808'}]
tags: [ACL, Datasets, Reinforcement Learning, Language Modeling, Alt]
---
Commonsense question answering (QA) requires a model to grasp commonsense and
factual knowledge to answer questions about world events. Many prior methods
couple language modeling with knowledge graphs (KG). However, although a KG
contains rich structural information, it lacks the context to provide a more
precise understanding of the concepts. This creates a gap when fusing knowledge
graphs into language modeling, especially when there is insufficient labeled
data. Thus, we propose to employ external entity descriptions to provide
contextual information for knowledge understanding. We retrieve descriptions of
related concepts from Wiktionary and feed them as additional input to
pre-trained language models. The resulting model achieves state-of-the-art
result in the CommonsenseQA dataset and the best result among non-generative
models in OpenBookQA.