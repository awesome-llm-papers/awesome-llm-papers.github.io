---
layout: publication
title: 'One Task Vector Is Not Enough: A Large-scale Study For In-context Learning'
authors: Tikhonov Pavel, Oseledets Ivan, Tutubalina Elena
conference: Advances in Kernel Methods
year: 2025
bibkey: tikhonov2025one
citations: 353
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.23911'}]
tags: [Few Shot, Evaluation, Datasets, In Context Learning]
---
In-context learning (ICL) enables Large Language Models (LLMs) to adapt to new tasks using few examples, with task vectors - specific hidden state activations - hypothesized to encode task information. Existing studies are limited by small-scale benchmarks, restricting comprehensive analysis. We introduce QuiteAFew, a novel dataset of 3,096 diverse few-shot tasks, each with 30 input-output pairs derived from the Alpaca dataset. Experiments with Llama-3-8B on QuiteAFew reveal: (1) task vector performance peaks at an intermediate layer (e.g., 15th), (2) effectiveness varies significantly by task type, and (3) complex tasks rely on multiple, subtask-specific vectors rather than a single vector, suggesting distributed task knowledge representation.