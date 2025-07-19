---
layout: publication
title: Evaluating The Use Of Llms For Documentation To Code Traceability
authors: Alor Ebube, Khatoonabadi Sayedhassan, Shihab Emad
conference: IEEE Transactions on Software Engineering
year: 2025
bibkey: alor2025evaluating
citations: 694
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.16440'}]
tags: [Model Architecture, Tools, Interpretability And Explainability, BERT, Evaluation,
  LLM For Code, LLM for Code, GPT, Datasets, Reinforcement Learning]
---
Large Language Models (LLMs) offer new potential for automating documentation-to-code traceability, yet their capabilities remain underexplored. We present a comprehensive evaluation of LLMs (Claude 3.5 Sonnet, GPT-4o, and o3-mini) in establishing trace links between various software documentation (including API references and user guides) and source code. We create two novel datasets from two open-source projects (Unity Catalog and Crawl4AI). Through systematic experiments, we assess three key capabilities: (1) trace link identification accuracy, (2) relationship explanation quality, and (3) multi-step chain reconstruction. Results show that the best-performing LLM achieves F1-scores of 79.4% and 80.4% across the two datasets, substantially outperforming our baselines (TF-IDF, BM25, and CodeBERT). While fully correct relationship explanations range from 42.9% to 71.1%, partial accuracy exceeds 97%, indicating that fundamental connections are rarely missed. For multi-step chains, LLMs maintain high endpoint accuracy but vary in capturing precise intermediate links. Error analysis reveals that many false positives stem from naming-based assumptions, phantom links, or overgeneralization of architectural patterns. We demonstrate that task-framing, such as a one-to-many matching strategy, is critical for performance. These findings position LLMs as powerful assistants for trace discovery, but their limitations could necessitate human-in-the-loop tool design and highlight specific error patterns for future research.