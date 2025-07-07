---
layout: publication
title: 'Spot: Better Frozen Model Adaptation Through Soft Prompt Transfer'
authors: Tu Vu, Brian Lester, Noah Constant, Rami Al-rfou, Daniel Cer
conference: Arxiv
year: 2021
citations: 40
bibkey: vu2021better
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.07904'}]
tags: [Fine-Tuning, Prompting]
---
There has been growing interest in parameter-efficient methods to apply
pre-trained language models to downstream tasks. Building on the Prompt Tuning
approach of Lester et al. (2021), which learns task-specific soft prompts to
condition a frozen pre-trained model to perform different tasks, we propose a
novel prompt-based transfer learning approach called SPoT: Soft Prompt
Transfer. SPoT first learns a prompt on one or more source tasks and then uses
it to initialize the prompt for a target task. We show that SPoT significantly
boosts the performance of Prompt Tuning across many tasks. More remarkably,
across all model sizes, SPoT matches or outperforms standard Model Tuning
(which fine-tunes all model parameters) on the SuperGLUE benchmark, while using
up to 27,000x fewer task-specific parameters. To understand where SPoT is most
effective, we conduct a large-scale study on task transferability with 26 NLP
tasks in 160 combinations, and demonstrate that many tasks can benefit each
other via prompt transfer. Finally, we propose an efficient retrieval approach
that interprets task prompts as task embeddings to identify similar tasks and
predict the most transferable source tasks for a novel target task.