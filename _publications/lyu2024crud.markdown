---
layout: publication
title: 'CRUD-RAG: A Comprehensive Chinese Benchmark For Retrieval-augmented Generation
  Of Large Language Models'
authors: Yuanjie Lyu et al.
conference: ACM Transactions on Information Systems
year: 2024
citations: 16
bibkey: lyu2024crud
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2401.17043'}]
tags: [Reinforcement Learning, Evaluation, RAG, Applications]
---
Retrieval-Augmented Generation (RAG) is a technique that enhances the
capabilities of large language models (LLMs) by incorporating external
knowledge sources. This method addresses common LLM limitations, including
outdated information and the tendency to produce inaccurate "hallucinated"
content. However, the evaluation of RAG systems is challenging, as existing
benchmarks are limited in scope and diversity. Most of the current benchmarks
predominantly assess question-answering applications, overlooking the broader
spectrum of situations where RAG could prove advantageous. Moreover, they only
evaluate the performance of the LLM component of the RAG pipeline in the
experiments, and neglect the influence of the retrieval component and the
external knowledge database. To address these issues, this paper constructs a
large-scale and more comprehensive benchmark, and evaluates all the components
of RAG systems in various RAG application scenarios. Specifically, we have
categorized the range of RAG applications into four distinct types-Create,
Read, Update, and Delete (CRUD), each representing a unique use case. "Create"
refers to scenarios requiring the generation of original, varied content.
"Read" involves responding to intricate questions in knowledge-intensive
situations. "Update" focuses on revising and rectifying inaccuracies or
inconsistencies in pre-existing texts. "Delete" pertains to the task of
summarizing extensive texts into more concise forms. For each of these CRUD
categories, we have developed comprehensive datasets to evaluate the
performance of RAG systems. We also analyze the effects of various components
of the RAG system, such as the retriever, the context length, the knowledge
base construction, and the LLM. Finally, we provide useful insights for
optimizing the RAG technology for different scenarios.