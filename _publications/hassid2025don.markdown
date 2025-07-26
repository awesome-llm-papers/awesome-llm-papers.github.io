---
layout: publication
title: Don't Overthink It. Preferring Shorter Thinking Chains For Improved LLM Reasoning
authors: Michael Hassid, Gabriel Synnaeve, Yossi Adi, Roy Schwartz
conference: No Venue
year: 2025
bibkey: hassid2025don
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.17813'}]
tags: ["Training Techniques"]
short_authors: Hassid et al.
---
Reasoning large language models (LLMs) heavily rely on scaling test-time compute to perform complex reasoning tasks by generating extensive "thinking" chains. While demonstrating impressive results, this approach incurs significant computational costs and inference time. In this work, we challenge the assumption that long thinking chains results in better reasoning capabilities. We first demonstrate that shorter reasoning chains within individual questions are significantly more likely to yield correct answers - up to 34.5% more accurate than the longest chain sampled for the same question. Based on these results, we suggest short-m@k, a novel reasoning LLM inference method. Our method executes k independent generations in parallel and halts computation once the first m thinking processes are done. The final answer is chosen using majority voting among these m chains. Basic short-1@k demonstrates similar or even superior performance over standard majority voting in low-compute settings - using up to 40% fewer thinking tokens. short-3@k, while slightly less efficient than short-1@k, consistently surpasses majority voting across all compute budgets, while still being substantially faster (up to 33% wall time reduction). Inspired by our results, we finetune an LLM using short, long, and randomly selected reasoning chains. We then observe that training on the shorter ones leads to better performance. Our findings suggest rethinking current methods of test-time compute in reasoning LLMs, emphasizing that longer "thinking" does not necessarily translate to improved performance and can, counter-intuitively, lead to degraded results.

https://huggingface.co/discussions/paper/68368b77b399c7d3af07119c