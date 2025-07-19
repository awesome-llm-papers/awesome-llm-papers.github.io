---
layout: publication
title: 'W-RAG: Weakly Supervised Dense Retrieval In RAG For Open-domain Question Answering'
authors: Nian et al.
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2024
bibkey: nian2024w
citations: 208
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2408.08444'}]
tags: [Fine Tuning, Training Techniques, ACL, RAG, Datasets, Alt]
---
In knowledge-intensive tasks such as open-domain question answering (OpenQA),
large language models (LLMs) often struggle to generate factual answers,
relying solely on their internal (parametric) knowledge. To address this
limitation, Retrieval-Augmented Generation (RAG) systems enhance LLMs by
retrieving relevant information from external sources, thereby positioning the
retriever as a pivotal component. Although dense retrieval demonstrates
state-of-the-art performance, its training poses challenges due to the scarcity
of ground-truth evidence, largely attributed to the high costs of human
annotation. In this paper, we propose W-RAG, a method that draws weak training
signals from the downstream task (such as OpenQA) of an LLM, and fine-tunes the
retriever to prioritize passages that most benefit the task. Specifically, we
rerank the top-\\(k\\) passages retrieved via BM25 by assessing the probability
that the LLM will generate the correct answer for a question given each
passage. The highest-ranking passages are then used as positive fine-tuning
examples for dense retrieval. We conduct comprehensive experiments across four
publicly available OpenQA datasets to demonstrate that our approach enhances
both retrieval and OpenQA performance compared to baseline models, achieving
results comparable to models fine-tuned with human-labeled data.