---
layout: publication
title: A Mapreduce Approach To Effectively Utilize Long Context Information In Retrieval
  Augmented Language Models
authors: Zhang et al.
conference: Transactions of the Association for Computational Linguistics
year: 2024
bibkey: zhang2024mapreduce
citations: 130
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.15271'}]
tags: [Security, TACL, ACL, RAG, Datasets, Responsible AI, Alt]
---
While holding great promise for improving and facilitating healthcare, large
language models (LLMs) struggle to produce up-to-date responses on evolving
topics due to outdated knowledge or hallucination. Retrieval-augmented
generation (RAG) is a pivotal innovation that improves the accuracy and
relevance of LLM responses by integrating LLMs with a search engine and
external sources of knowledge. However, the quality of RAG responses can be
largely impacted by the rank and density of key information in the retrieval
results, such as the "lost-in-the-middle" problem. In this work, we aim to
improve the robustness and reliability of the RAG workflow in the medical
domain. Specifically, we propose a map-reduce strategy, BriefContext, to combat
the "lost-in-the-middle" issue without modifying the model weights. We
demonstrated the advantage of the workflow with various LLM backbones and on
multiple QA datasets. This method promises to improve the safety and
reliability of LLMs deployed in healthcare domains.