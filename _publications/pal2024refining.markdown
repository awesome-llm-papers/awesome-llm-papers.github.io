---
layout: publication
title: Refining Answer Distributions For Improved Large Language Model Reasoning
authors: Pal et al.
conference: JAMA Network Open
year: 2024
bibkey: pal2024refining
citations: 163
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.13292'}]
tags: [RAG, Prompting, Tools, Evaluation, Reinforcement Learning, Datasets]
---
Large Language Models (LLMs) have exhibited an impressive capability to
perform reasoning tasks, especially if they are encouraged to generate a
sequence of intermediate steps. Reasoning performance can be improved by
suitably combining multiple LLM responses, generated either in parallel in a
single query, or via sequential interactions with LLMs throughout the reasoning
process. Existing strategies for combination, such as self-consistency and
progressive-hint-prompting, make inefficient usage of the LLM responses. We
present Refined Answer Distributions, a novel and principled algorithmic
framework to enhance the reasoning capabilities of LLMs. Our approach can be
viewed as an iterative sampling strategy for forming a Monte Carlo
approximation of an underlying distribution of answers, with the goal of
identifying the mode -- the most likely answer. Empirical evaluation on several
reasoning benchmarks demonstrates the superiority of the proposed approach.