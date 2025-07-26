---
layout: publication
title: 'Saferag: Benchmarking Security In Retrieval-augmented Generation Of Large
  Language Model'
authors: Xun Liang, Simin Niu, Zhiyu Li, Sensen Zhang, Hanyu Wang, Feiyu Xiong, Jason
  Zhaoxin Fan, Bo Tang, Shichao Song, Mengwei Wang, Jiawei Yang
conference: No Venue
year: 2025
bibkey: liang2025saferag
additional_links: [{name: Code, url: 'https://github.com/IAAR-Shanghai/SafeRAG'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67a1bfc414cba2eba6da4b63'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2501.18636'}]
tags: ["Evaluation", "RAG", "Security"]
short_authors: Liang et al.
---
The indexing-retrieval-generation paradigm of retrieval-augmented generation (RAG) has been highly successful in solving knowledge-intensive tasks by integrating external knowledge into large language models (LLMs). However, the incorporation of external and unverified knowledge increases the vulnerability of LLMs because attackers can perform attack tasks by manipulating knowledge. In this paper, we introduce a benchmark named SafeRAG designed to evaluate the RAG security. First, we classify attack tasks into silver noise, inter-context conflict, soft ad, and white Denial-of-Service. Next, we construct RAG security evaluation dataset (i.e., SafeRAG dataset) primarily manually for each task. We then utilize the SafeRAG dataset to simulate various attack scenarios that RAG may encounter. Experiments conducted on 14 representative RAG components demonstrate that RAG exhibits significant vulnerability to all attack tasks and even the most apparent attack task can easily bypass existing retrievers, filters, or advanced LLMs, resulting in the degradation of RAG service quality. Code is available at: https://github.com/IAAR-Shanghai/SafeRAG.

https://huggingface.co/discussions/paper/67a1bfc414cba2eba6da4b63