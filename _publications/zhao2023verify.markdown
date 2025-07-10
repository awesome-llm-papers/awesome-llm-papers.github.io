---
layout: publication
title: 'Verify-and-edit: A Knowledge-enhanced Chain-of-thought Framework'
authors: Ruochen Zhao, Xingxuan Li, Shafiq Joty, Chengwei Qin, Lidong Bing
conference: 'Proceedings of the 61st Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2023
citations: 26
bibkey: zhao2023verify
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.03268'}]
tags: [Model Architecture, Applications, Tools, Prompting, GPT]
---
As large language models (LLMs) have become the norm in NLP, demonstrating
good performance in generation and reasoning tasks, one of its most fatal
disadvantages is the lack of factual correctness. Generating unfactual texts
not only leads to lower performances but also degrades the trust and validity
of their applications. Chain-of-Thought (CoT) prompting improves trust and
model performance on complex reasoning tasks by generating interpretable
reasoning chains, but still suffers from factuality concerns in
knowledge-intensive tasks. In this paper, we propose the Verify-and-Edit
framework for CoT prompting, which seeks to increase prediction factuality by
post-editing reasoning chains according to external knowledge. Building on top
of GPT-3, our framework lead to accuracy improvements in multiple open-domain
question-answering tasks.