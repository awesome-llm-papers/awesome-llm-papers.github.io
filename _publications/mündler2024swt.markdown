---
layout: publication
title: 'Swt-bench: Testing And Validating Real-world Bug-fixes With Code Agents'
authors: "M\xFCndler et al."
conference: 2015 IEEE/ACM 37th IEEE International Conference on Software Engineering
year: 2024
bibkey: "m\xFCndler2024swt"
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.12952'}]
tags: [Evaluation, LLM For Code, Agentic, LLM for Code, RAG, Datasets, Reinforcement
    Learning]
---
Rigorous software testing is crucial for developing and maintaining
high-quality code, making automated test generation a promising avenue for both
improving software quality and boosting the effectiveness of code generation
methods. However, while code generation with Large Language Models (LLMs) is an
extraordinarily active research area, test generation remains relatively
unexplored. We address this gap and investigate the capability of LLM-based
Code Agents to formalize user issues into test cases. To this end, we propose a
novel benchmark based on popular GitHub repositories, containing real-world
issues, ground-truth bug-fixes, and golden tests. We find that LLMs generally
perform surprisingly well at generating relevant test cases, with Code Agents
designed for code repair exceeding the performance of systems designed
specifically for test generation. Further, as test generation is a similar but
more structured task than code generation, it allows for a more fine-grained
analysis using issue reproduction rate and coverage changes, providing a dual
metric for analyzing systems designed for code repair. Finally, we find that
generated tests are an effective filter for proposed code fixes, doubling the
precision of SWE-Agent. We release all data and code at
https://github.com/logic-star-ai/SWT-Bench