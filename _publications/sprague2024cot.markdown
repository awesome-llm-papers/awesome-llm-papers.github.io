---
layout: publication
title: To Cot Or Not To Cot? Chain-of-thought Helps Mainly On Math And Symbolic Reasoning
authors: Zayne Sprague, Fangcong Yin, Juan Diego Rodriguez, Dongwei Jiang, Manya Wadhwa,
  Prasann Singhal, Xinyu Zhao, Xi Ye, Kyle Mahowald, Greg Durrett
conference: No Venue
year: 2024
bibkey: sprague2024cot
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2409.12183'}]
tags: ["Applications", "Datasets", "Evaluation Frameworks", "Prompting", "Survey Paper"]
short_authors: Sprague et al.
---
Chain-of-thought (CoT) via prompting is the de facto method for eliciting reasoning capabilities from large language models (LLMs). But for what kinds of tasks is this extra ``thinking'' really helpful? To analyze this, we conducted a quantitative meta-analysis covering over 100 papers using CoT and ran our own evaluations of 20 datasets across 14 models. Our results show that CoT gives strong performance benefits primarily on tasks involving math or logic, with much smaller gains on other types of tasks. On MMLU, directly generating the answer without CoT leads to almost identical accuracy as CoT unless the question or model's response contains an equals sign, indicating symbolic operations and reasoning. Following this finding, we analyze the behavior of CoT on these problems by separating planning and execution and comparing against tool-augmented LLMs. Much of CoT's gain comes from improving symbolic execution, but it underperforms relative to using a symbolic solver. Our results indicate that CoT can be applied selectively, maintaining performance while saving inference costs. Furthermore, they suggest a need to move beyond prompt-based CoT to new paradigms that better leverage intermediate computation across the whole range of LLM applications.

https://huggingface.co/discussions/paper/66eb8d15e0f57407e06a604a