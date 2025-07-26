---
layout: publication
title: 'Memorag: Moving Towards Next-gen RAG Via Memory-inspired Knowledge Discovery'
authors: Hongjin Qian, Peitian Zhang, Zheng Liu, Kelong Mao, Zhicheng Dou
conference: No Venue
year: 2024
bibkey: qian2024memorag
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2409.05591'}]
tags: ["RAG"]
short_authors: Qian et al.
---
Retrieval-Augmented Generation (RAG) leverages retrieval tools to access external databases, thereby enhancing the generation quality of large language models (LLMs) through optimized context. However, the existing retrieval methods are constrained inherently, as they can only perform relevance matching between explicitly stated queries and well-formed knowledge, but unable to handle tasks involving ambiguous information needs or unstructured knowledge. Consequently, existing RAG systems are primarily effective for straightforward question-answering tasks. In this work, we propose MemoRAG, a novel retrieval-augmented generation paradigm empowered by long-term memory. MemoRAG adopts a dual-system architecture. On the one hand, it employs a light but long-range LLM to form the global memory of database. Once a task is presented, it generates draft answers, cluing the retrieval tools to locate useful information within the database. On the other hand, it leverages an expensive but expressive LLM, which generates the ultimate answer based on the retrieved information. Building on this general framework, we further optimize MemoRAG's performance by enhancing its cluing mechanism and memorization capacity. In our experiment, MemoRAG achieves superior performance across a variety of evaluation tasks, including both complex ones where conventional RAG fails and straightforward ones where RAG is commonly applied.

https://huggingface.co/discussions/paper/66e000975511a2f2f73252b2