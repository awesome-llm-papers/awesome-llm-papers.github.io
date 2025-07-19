---
layout: publication
title: 'CARTS: Collaborative Agents For Recommendation Textual Summarization'
authors: Chen et al.
conference: Expert Systems with Applications
year: 2025
bibkey: chen2025carts
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.17765'}]
tags: [Interpretability And Explainability, Agentic, Tools, Evaluation, Applications]
---
Current recommendation systems often require some form of textual data summarization, such as generating concise and coherent titles for product carousels or other grouped item displays. While large language models have shown promise in NLP domains for textual summarization, these approaches do not directly apply to recommendation systems, where explanations must be highly relevant to the core features of item sets, adhere to strict word limit constraints. In this paper, we propose CARTS (Collaborative Agents for Recommendation Textual Summarization), a multi-agent LLM framework designed for structured summarization in recommendation systems. CARTS decomposes the task into three stages-Generation Augmented Generation (GAG), refinement circle, and arbitration, where successive agent roles are responsible for extracting salient item features, iteratively refining candidate titles based on relevance and length feedback, and selecting the final title through a collaborative arbitration process. Experiments on large-scale e-commerce data and live A/B testing show that CARTS significantly outperforms single-pass and chain-of-thought LLM baselines, delivering higher title relevance and improved user engagement metrics.