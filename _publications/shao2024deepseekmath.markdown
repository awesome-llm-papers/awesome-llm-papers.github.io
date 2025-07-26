---
layout: publication
title: 'Deepseekmath: Pushing The Limits Of Mathematical Reasoning In Open Language
  Models'
authors: Zhihong Shao, Peiyi Wang, Qihao Zhu, Runxin Xu, Junxiao Song, Mingchuan Zhang,
  Y. K. Li, Y. Wu, Daya Guo
conference: No Venue
year: 2024
bibkey: shao2024deepseekmath
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/65c19a2055c4f06fa9692c9b'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2402.03300'}]
tags: ["Model Architecture"]
short_authors: Shao et al.
---
Mathematical reasoning poses a significant challenge for language models due to its complex and structured nature. In this paper, we introduce DeepSeekMath 7B, which continues pre-training DeepSeek-Coder-Base-v1.5 7B with 120B math-related tokens sourced from Common Crawl, together with natural language and code data. DeepSeekMath 7B has achieved an impressive score of 51.7% on the competition-level MATH benchmark without relying on external toolkits and voting techniques, approaching the performance level of Gemini-Ultra and GPT-4. Self-consistency over 64 samples from DeepSeekMath 7B achieves 60.9% on MATH. The mathematical reasoning capability of DeepSeekMath is attributed to two key factors: First, we harness the significant potential of publicly available web data through a meticulously engineered data selection pipeline. Second, we introduce Group Relative Policy Optimization (GRPO), a variant of Proximal Policy Optimization (PPO), that enhances mathematical reasoning abilities while concurrently optimizing the memory usage of PPO.

https://huggingface.co/discussions/paper/65c19a2055c4f06fa9692c9b