---
layout: publication
title: 'Zerodl: Zero-shot Distribution Learning For Text Clustering Via Large Language
  Models'
authors: Jo et al.
conference: Proceedings of the 32nd ACM SIGSOFT International Symposium on Software
  Testing and Analysis
year: 2024
bibkey: jo2024zerodl
citations: 147
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.13342'}]
tags: [Prompting, Datasets]
---
The advancements in large language models (LLMs) have brought significant progress in NLP tasks. However, if a task cannot be fully described in prompts, the models could fail to carry out the task. In this paper, we propose a simple yet effective method to contextualize a task toward a LLM. The method utilizes (1) open-ended zero-shot inference from the entire dataset, (2) aggregate the inference results, and (3) finally incorporate the aggregated meta-information for the actual task. We show the effectiveness in text clustering tasks, empowering LLMs to perform text-to-text-based clustering and leading to improvements on several datasets. Furthermore, we explore the generated class labels for clustering, showing how the LLM understands the task through data.