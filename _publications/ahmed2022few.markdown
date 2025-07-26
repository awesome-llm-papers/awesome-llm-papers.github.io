---
layout: publication
title: Few-shot Training Llms For Project-specific Code-summarization
authors: Toufique Ahmed, Premkumar Devanbu
conference: Proceedings of the 37th IEEE/ACM International Conference on Automated
  Software Engineering
year: 2022
bibkey: ahmed2022few
citations: 119
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2207.04237'}]
tags: ["Few-Shot", "Llm For Code", "Model Architecture", "Training Techniques"]
short_authors: Toufique Ahmed, Premkumar Devanbu
---
Very large language models (LLMs), such as GPT-3 and Codex have achieved
state-of-the-art performance on several natural-language tasks, and show great
promise also for code. A particularly exciting aspect of LLMs is their knack
for few-shot and zero-shot learning: they can learn to perform a task with very
few examples. Few-shotting has particular synergies in software engineering,
where there are a lot of phenomena (identifier names, APIs, terminology, coding
patterns) that are known to be highly project-specific. However,
project-specific data can be quite limited, especially early in the history of
a project; thus the few-shot learning capacity of LLMs might be very relevant.
In this paper, we investigate the use few-shot training with the very large GPT
(Generative Pre-trained Transformer) Codex model, and find evidence suggesting
that one can significantly surpass state-of-the-art models for
code-summarization, leveraging project-specific training.