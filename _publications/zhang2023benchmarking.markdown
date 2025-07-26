---
layout: publication
title: Benchmarking Large Language Models For News Summarization
authors: Tianyi Zhang, Faisal Ladhak, Esin Durmus, Percy Liang, Kathleen Mckeown,
  Tatsunori B. Hashimoto
conference: Transactions of the Association for Computational Linguistics
year: 2024
bibkey: zhang2023benchmarking
citations: 130
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2301.13848'}]
tags: ["Evaluation", "TACL"]
short_authors: Zhang et al.
---
Large language models (LLMs) have shown promise for automatic summarization
but the reasons behind their successes are poorly understood. By conducting a
human evaluation on ten LLMs across different pretraining methods, prompts, and
model scales, we make two important observations. First, we find instruction
tuning, and not model size, is the key to the LLM's zero-shot summarization
capability. Second, existing studies have been limited by low-quality
references, leading to underestimates of human performance and lower few-shot
and finetuning performance. To better evaluate LLMs, we perform human
evaluation over high-quality summaries we collect from freelance writers.
Despite major stylistic differences such as the amount of paraphrasing, we find
that LMM summaries are judged to be on par with human written summaries.