---
layout: publication
title: Retrieval Augmented Code Generation And Summarization
authors: Parvez et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2021'
year: 2021
bibkey: parvez2021retrieval
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2108.11601'}]
tags: [Tools, LLM For Code, Evaluation, EMNLP, ACL, Datasets]
---
Software developers write a lot of source code and documentation during
software development. Intrinsically, developers often recall parts of source
code or code summaries that they had written in the past while implementing
software or documenting them. To mimic developers' code or summary generation
behavior, we propose a retrieval augmented framework, REDCODER, that retrieves
relevant code or summaries from a retrieval database and provides them as a
supplement to code generation or summarization models. REDCODER has a couple of
uniqueness. First, it extends the state-of-the-art dense retrieval technique to
search for relevant code or summaries. Second, it can work with retrieval
databases that include unimodal (only code or natural language description) or
bimodal instances (code-description pairs). We conduct experiments and
extensive analysis on two benchmark datasets of code generation and
summarization in Java and Python, and the promising results endorse the
effectiveness of our proposed retrieval augmented framework.