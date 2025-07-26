---
layout: publication
title: Chain-of-retrieval Augmented Generation
authors: Liang Wang, Haonan Chen, Nan Yang, Xiaolong Huang, Zhicheng Dou, Furu Wei
conference: No Venue
year: 2025
bibkey: wang2025chain
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.14342'}]
tags: ["RAG"]
short_authors: Wang et al.
---
This paper introduces an approach for training o1-like RAG models that retrieve and reason over relevant information step by step before generating the final answer. Conventional RAG methods usually perform a single retrieval step before the generation process, which limits their effectiveness in addressing complex queries due to imperfect retrieval results. In contrast, our proposed method, CoRAG (Chain-of-Retrieval Augmented Generation), allows the model to dynamically reformulate the query based on the evolving state. To train CoRAG effectively, we utilize rejection sampling to automatically generate intermediate retrieval chains, thereby augmenting existing RAG datasets that only provide the correct final answer. At test time, we propose various decoding strategies to scale the model's test-time compute by controlling the length and number of sampled retrieval chains. Experimental results across multiple benchmarks validate the efficacy of CoRAG, particularly in multi-hop question answering tasks, where we observe more than 10 points improvement in EM score compared to strong baselines. On the KILT benchmark, CoRAG establishes a new state-of-the-art performance across a diverse range of knowledge-intensive tasks. Furthermore, we offer comprehensive analyses to understand the scaling behavior of CoRAG, laying the groundwork for future research aimed at developing factual and grounded foundation models.

https://huggingface.co/discussions/paper/6796fa2d4fccd4b951e8ab4e