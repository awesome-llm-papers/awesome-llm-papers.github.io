---
layout: publication
title: 'Connecting The Dots: A Knowledgeable Path Generator For Commonsense Question
  Answering'
authors: Wang et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: wang2020connecting
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.00691'}]
tags: [Tools, Training Techniques, Fine Tuning, Evaluation, ACL, EMNLP, RAG, Datasets]
---
Commonsense question answering (QA) requires background knowledge which is
not explicitly stated in a given context. Prior works use commonsense knowledge
graphs (KGs) to obtain this knowledge for reasoning. However, relying entirely
on these KGs may not suffice, considering their limited coverage and the
contextual dependence of their knowledge. In this paper, we augment a general
commonsense QA framework with a knowledgeable path generator. By extrapolating
over existing paths in a KG with a state-of-the-art language model, our
generator learns to connect a pair of entities in text with a dynamic, and
potentially novel, multi-hop relational path. Such paths can provide structured
evidence for solving commonsense questions without fine-tuning the path
generator. Experiments on two datasets show the superiority of our method over
previous works which fully rely on knowledge from KGs (with up to 6%
improvement in accuracy), across various amounts of training data. Further
evaluation suggests that the generated paths are typically interpretable,
novel, and relevant to the task.