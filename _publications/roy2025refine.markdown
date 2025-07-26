---
layout: publication
title: 'REFINE-AF: A Task-agnostic Framework To Align Language Models Via Self-generated
  Instructions Using Reinforcement Learning From Automated Feedback'
authors: Aniruddha Roy, Pretam Ray, Abhilash Nandy, Somak Aditya, Pawan Goyal
conference: No Venue
year: 2025
bibkey: roy2025refine
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.06548'}]
tags: ["Tools"]
short_authors: Roy et al.
---
Instruction-based Large Language Models (LLMs) have proven effective in numerous few-shot or zero-shot Natural Language Processing (NLP) tasks. However, creating human-annotated instruction data is time-consuming, expensive, and often limited in quantity and task diversity. Previous research endeavors have attempted to address this challenge by proposing frameworks capable of generating instructions in a semi-automated and task-agnostic manner directly from the model itself. Many of these efforts have relied on large API-only parameter-based models such as GPT-3.5 (175B), which are expensive, and subject to limits on a number of queries. This paper explores the performance of three open-source small LLMs such as LLaMA 2-7B, LLama 2-13B, and Mistral 7B, using a semi-automated framework, thereby reducing human intervention, effort, and cost required to generate an instruction dataset for fine-tuning LLMs. Furthermore, we demonstrate that incorporating a Reinforcement Learning (RL) based training algorithm into this LLMs-based framework leads to further enhancements. Our evaluation of the dataset reveals that these RL-based frameworks achieve a substantial improvements in 63-66% of the tasks compared to previous approaches.

https://huggingface.co/discussions/paper/6822a0f8f90521b5d8cb45c1