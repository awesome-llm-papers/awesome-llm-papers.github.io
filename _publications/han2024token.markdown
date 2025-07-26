---
layout: publication
title: Token-budget-aware LLM Reasoning
authors: Tingxu Han, Chunrong Fang, Shiyu Zhao, Shiqing Ma, Zhenyu Chen, Zhenting
  Wang
conference: No Venue
year: 2024
bibkey: han2024token
additional_links: [{name: Code, url: 'https://github.com/GeniusHTX/TALE'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/676c40d719a21c8b928d13ea'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2412.18547'}]
tags: ["Efficiency"]
short_authors: Han et al.
---
Reasoning is critical for large language models (LLMs) to excel in a wide range of tasks. While methods like Chain-of-Thought (CoT) reasoning enhance LLM performance by decomposing problems into intermediate steps, they also incur significant overhead in token usage, leading to increased costs. We find that the reasoning process of current LLMs is unnecessarily lengthy and it can be compressed by including a reasonable token budget in the prompt, but the choice of token budget plays a crucial role in the actual compression effectiveness. We then propose a token-budget-aware LLM reasoning framework, which dynamically estimates token budgets for different problems based on reasoning complexity and uses the estimated token budgets to guide the reasoning process. Experiments show that our method effectively reduces token costs in CoT reasoning with only a slight performance reduction, offering a practical solution to balance efficiency and accuracy in LLM reasoning. Code: https://github.com/GeniusHTX/TALE.

https://huggingface.co/discussions/paper/676c40d719a21c8b928d13ea