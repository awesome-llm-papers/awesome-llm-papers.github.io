---
layout: publication
title: 'BEIR: A Heterogenous Benchmark For Zero-shot Evaluation Of Information Retrieval
  Models'
authors: "Nandan Thakur, Nils Reimers, Andreas R\xFCckl\xE9, Abhishek Srivastava,\
  \ Iryna Gurevych"
conference: Arxiv
year: 2021
bibkey: thakur2021beir
citations: 96
additional_links: [{name: Code, url: 'https://github.com/UKPLab/beir'}, {name: Paper,
    url: 'https://arxiv.org/abs/2104.08663'}]
tags: ["Datasets", "Evaluation", "Retrieval Systems"]
short_authors: Thakur et al.
---
Existing neural information retrieval (IR) models have often been studied in
homogeneous and narrow settings, which has considerably limited insights into
their out-of-distribution (OOD) generalization capabilities. To address this,
and to facilitate researchers to broadly evaluate the effectiveness of their
models, we introduce Benchmarking-IR (BEIR), a robust and heterogeneous
evaluation benchmark for information retrieval. We leverage a careful selection
of 18 publicly available datasets from diverse text retrieval tasks and domains
and evaluate 10 state-of-the-art retrieval systems including lexical, sparse,
dense, late-interaction and re-ranking architectures on the BEIR benchmark. Our
results show BM25 is a robust baseline and re-ranking and
late-interaction-based models on average achieve the best zero-shot
performances, however, at high computational costs. In contrast, dense and
sparse-retrieval models are computationally more efficient but often
underperform other approaches, highlighting the considerable room for
improvement in their generalization capabilities. We hope this framework allows
us to better evaluate and understand existing retrieval systems, and
contributes to accelerating progress towards better robust and generalizable
systems in the future. BEIR is publicly available at
https://github.com/UKPLab/beir.