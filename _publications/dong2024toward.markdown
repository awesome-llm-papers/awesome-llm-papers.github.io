---
layout: publication
title: Toward General Instruction-following Alignment For Retrieval-augmented Generation
authors: Guanting Dong, Xiaoshuai Song, Yutao Zhu, Runqi Qiao, Zhicheng Dou, Ji-rong
  Wen
conference: No Venue
year: 2024
bibkey: dong2024toward
additional_links: [{name: Code, url: 'https://FollowRAG.github.io'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/670dcefc487a5e24b2768f16'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2410.09584'}]
tags: ["RAG"]
short_authors: Dong et al.
---
Following natural instructions is crucial for the effective application of Retrieval-Augmented Generation (RAG) systems. Despite recent advancements in Large Language Models (LLMs), research on assessing and improving instruction-following (IF) alignment within the RAG domain remains limited. To address this issue, we propose VIF-RAG, the first automated, scalable, and verifiable synthetic pipeline for instruction-following alignment in RAG systems. We start by manually crafting a minimal set of atomic instructions (<100) and developing combination rules to synthesize and verify complex instructions for a seed set. We then use supervised models for instruction rewriting while simultaneously generating code to automate the verification of instruction quality via a Python executor. Finally, we integrate these instructions with extensive RAG and general data samples, scaling up to a high-quality VIF-RAG-QA dataset (>100k) through automated processes. To further bridge the gap in instruction-following auto-evaluation for RAG systems, we introduce FollowRAG Benchmark, which includes approximately 3K test samples, covering 22 categories of general instruction constraints and four knowledge-intensive QA datasets. Due to its robust pipeline design, FollowRAG can seamlessly integrate with different RAG benchmarks. Using FollowRAG and eight widely-used IF and foundational abilities benchmarks for LLMs, we demonstrate that VIF-RAG markedly enhances LLM performance across a broad range of general instruction constraints while effectively leveraging its capabilities in RAG scenarios. Further analysis offers practical insights for achieving IF alignment in RAG systems. Our code and datasets are released at https://FollowRAG.github.io.

https://huggingface.co/discussions/paper/670dcefc487a5e24b2768f16