---
layout: publication
title: Detecting Knowledge Boundary Of Vision Large Language Models By Sampling-based
  Inference
authors: Chen et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2025
bibkey: chen2025detecting
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.18023'}]
tags: [RAG, AAAI, Datasets]
---
Despite the advancements made in Visual Large Language Models (VLLMs), like text Large Language Models (LLMs), they have limitations in addressing questions that require real-time information or are knowledge-intensive. Indiscriminately adopting Retrieval Augmented Generation (RAG) techniques is an effective yet expensive way to enable models to answer queries beyond their knowledge scopes. To mitigate the dependence on retrieval and simultaneously maintain, or even improve, the performance benefits provided by retrieval, we propose a method to detect the knowledge boundary of VLLMs, allowing for more efficient use of techniques like RAG. Specifically, we propose a method with two variants that fine-tunes a VLLM on an automatically constructed dataset for boundary identification. Experimental results on various types of Visual Question Answering datasets show that our method successfully depicts a VLLM's knowledge boundary based on which we are able to reduce indiscriminate retrieval while maintaining or improving the performance. In addition, we show that the knowledge boundary identified by our method for one VLLM can be used as a surrogate boundary for other VLLMs. Code will be released at https://github.com/Chord-Chen-30/VLLM-KnowledgeBoundary