---
layout: publication
title: Beyond Chain-of-thought, Effective Graph-of-thought Reasoning In Language Models
authors: Yao Yao, Zuchao Li, Hai Zhao
conference: Arxiv
year: 2023
citations: 15
bibkey: yao2023beyond
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.16582'}]
tags: [Tools, Merging, Multimodal Models]
---
With the widespread use of language models (LMs) in NLP tasks, researchers
have discovered the potential of Chain-of-thought (CoT) to assist LMs in
accomplishing complex reasoning tasks by generating intermediate steps.
However, human thought processes are often non-linear, rather than simply
sequential chains of thoughts. Therefore, we propose Graph-of-Thought (GoT)
reasoning, which models human thought processes not only as a chain but also as
a graph. By representing thought units as nodes and connections between them as
edges, our approach captures the non-sequential nature of human thinking and
allows for a more realistic modeling of thought processes. GoT adopts a
two-stage framework with an additional GoT encoder for thought graph
representation and fuses the graph representation with the original input
representation through a gated fusion mechanism. We evaluate GoT's performance
on a text-only reasoning task (AQUA-RAT) and a multimodal reasoning task
(ScienceQA). Our model achieves significant improvement over the strong CoT
baseline on the AQUA-RAT test set and boosts accuracy from 85.19% to 87.59%
using the T5-base model over the state-of-the-art Multimodal-CoT on the
ScienceQA test set.