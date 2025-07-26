---
layout: publication
title: 'QA-GNN: Reasoning With Language Models And Knowledge Graphs For Question Answering'
authors: Michihiro Yasunaga, Hongyu Ren, Antoine Bosselut, Percy Liang, Jure Leskovec
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
bibkey: yasunaga2021qa
citations: 351
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.06378'}]
tags: ["NAACL", "Retrieval Systems"]
short_authors: Yasunaga et al.
---
The problem of answering questions using knowledge from pre-trained language
models (LMs) and knowledge graphs (KGs) presents two challenges: given a QA
context (question and answer choice), methods need to (i) identify relevant
knowledge from large KGs, and (ii) perform joint reasoning over the QA context
and KG. In this work, we propose a new model, QA-GNN, which addresses the above
challenges through two key innovations: (i) relevance scoring, where we use LMs
to estimate the importance of KG nodes relative to the given QA context, and
(ii) joint reasoning, where we connect the QA context and KG to form a joint
graph, and mutually update their representations through graph neural networks.
We evaluate our model on QA benchmarks in the commonsense (CommonsenseQA,
OpenBookQA) and biomedical (MedQA-USMLE) domains. QA-GNN outperforms existing
LM and LM+KG models, and exhibits capabilities to perform interpretable and
structured reasoning, e.g., correctly handling negation in questions.