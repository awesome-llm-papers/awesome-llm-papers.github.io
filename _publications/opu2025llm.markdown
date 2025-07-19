---
layout: publication
title: Llm-based Detection Of Tangled Code Changes For Higher-quality Method-level
  Bug Datasets
authors: Opu Md Nahidul Islam, Wang Shaowei, Chowdhury Shaiful
conference: 2013 10th Working Conference on Mining Software Repositories (MSR)
year: 2025
bibkey: opu2025llm
citations: 167
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.08263'}]
tags: [RAG, GPT, Prompting, Tools, Model Architecture, Few Shot, Datasets]
---
Tangled code changes-commits that conflate unrelated modifications such as bug fixes, refactorings, and enhancements-introduce significant noise into bug datasets and adversely affect the performance of bug prediction models. Addressing this issue at a fine-grained, method-level granularity remains underexplored. This is critical to address, as recent bug prediction models, driven by practitioner demand, are increasingly focusing on finer granularity rather than traditional class- or file-level predictions. This study investigates the utility of Large Language Models (LLMs) for detecting tangled code changes by leveraging both commit messages and method-level code diffs. We formulate the problem as a binary classification task and evaluate multiple prompting strategies, including zero-shot, few-shot, and chain-of-thought prompting, using state-of-the-art proprietary LLMs such as GPT-4o and Gemini-2.0-Flash.
  Our results demonstrate that combining commit messages with code diffs significantly enhances model performance, with the combined few-shot and chain-of-thought prompting achieving an F1-score of 0.88. Additionally, we explore embedding-based machine learning models trained on LLM-generated embeddings, where a multi-layer perceptron classifier achieves superior performance (F1-score: 0.906, MCC: 0.807). These findings are encouraging for the research community, as method-level bug prediction remains an open research problem, largely due to the lack of noise-free bug datasets. This research not only contributes a novel method-level perspective to the untangling problem but also highlights practical avenues for enhancing automated software quality assessment tools.