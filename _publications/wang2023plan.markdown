---
layout: publication
title: 'Plan-and-solve Prompting: Improving Zero-shot Chain-of-thought Reasoning By
  Large Language Models'
authors: Lei Wang, Wanyu Xu, Yihuai Lan, Zhiqiang Hu, Yunshi Lan, Roy Ka-wei Lee,
  Ee-peng Lim
conference: 'Proceedings of the 61st Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2023
bibkey: wang2023plan
citations: 94
additional_links: [{name: Code, url: 'https://github.com/AGI-Edgerunners/Plan-and-Solve-Prompting'},
  {name: Paper, url: 'https://arxiv.org/abs/2305.04091'}]
tags: ["Prompting"]
short_authors: Wang et al.
---
Large language models (LLMs) have recently been shown to deliver impressive
performance in various NLP tasks. To tackle multi-step reasoning tasks,
few-shot chain-of-thought (CoT) prompting includes a few manually crafted
step-by-step reasoning demonstrations which enable LLMs to explicitly generate
reasoning steps and improve their reasoning task accuracy. To eliminate the
manual effort, Zero-shot-CoT concatenates the target problem statement with
"Let's think step by step" as an input prompt to LLMs. Despite the success of
Zero-shot-CoT, it still suffers from three pitfalls: calculation errors,
missing-step errors, and semantic misunderstanding errors. To address the
missing-step errors, we propose Plan-and-Solve (PS) Prompting. It consists of
two components: first, devising a plan to divide the entire task into smaller
subtasks, and then carrying out the subtasks according to the plan. To address
the calculation errors and improve the quality of generated reasoning steps, we
extend PS prompting with more detailed instructions and derive PS+ prompting.
We evaluate our proposed prompting strategy on ten datasets across three
reasoning problems. The experimental results over GPT-3 show that our proposed
zero-shot prompting consistently outperforms Zero-shot-CoT across all datasets
by a large margin, is comparable to or exceeds Zero-shot-Program-of-Thought
Prompting, and has comparable performance with 8-shot CoT prompting on the math
reasoning problem. The code can be found at
https://github.com/AGI-Edgerunners/Plan-and-Solve-Prompting.