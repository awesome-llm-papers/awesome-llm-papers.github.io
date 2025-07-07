---
layout: publication
title: Hybrid Retrieval-generation Reinforced Agent For Medical Image Report Generation
authors: Christy Y. Li, Xiaodan Liang, Zhiting Hu, Eric P. Xing
conference: Arxiv
year: 2018
citations: 130
bibkey: li2018hybrid
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.08298'}]
tags: [RAG, Reinforcement Learning, Agentic]
---
Generating long and coherent reports to describe medical images poses
challenges to bridging visual patterns with informative human linguistic
descriptions. We propose a novel Hybrid Retrieval-Generation Reinforced Agent
(HRGR-Agent) which reconciles traditional retrieval-based approaches populated
with human prior knowledge, with modern learning-based approaches to achieve
structured, robust, and diverse report generation. HRGR-Agent employs a
hierarchical decision-making procedure. For each sentence, a high-level
retrieval policy module chooses to either retrieve a template sentence from an
off-the-shelf template database, or invoke a low-level generation module to
generate a new sentence. HRGR-Agent is updated via reinforcement learning,
guided by sentence-level and word-level rewards. Experiments show that our
approach achieves the state-of-the-art results on two medical report datasets,
generating well-balanced structured sentences with robust coverage of
heterogeneous medical report contents. In addition, our model achieves the
highest detection accuracy of medical terminologies, and improved human
evaluation performance.