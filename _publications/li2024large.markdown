---
layout: publication
title: Large Language Models Can Self-improve In Long-context Reasoning
authors: Siheng Li, Cheng Yang, Zesen Cheng, Lemao Liu, Mo Yu, Yujiu Yang, Wai Lam
conference: No Venue
year: 2024
bibkey: li2024large
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2411.08147'}]
tags: ["Memory & Context"]
short_authors: Li et al.
---
Large language models (LLMs) have achieved substantial progress in processing long contexts but still struggle with long-context reasoning. Existing approaches typically involve fine-tuning LLMs with synthetic data, which depends on annotations from human experts or advanced models like GPT-4, thus restricting further advancements. To address this issue, we investigate the potential for LLMs to self-improve in long-context reasoning and propose \ours, an approach specifically designed for this purpose. This approach is straightforward: we sample multiple outputs for each question, score them with Minimum Bayes Risk, and then apply supervised fine-tuning or preference optimization based on these outputs. Extensive experiments on several leading LLMs demonstrate the effectiveness of \ours, with an absolute improvement of 4.2 points for Llama-3.1-8B-Instruct. Furthermore, \ours achieves superior performance compared to prior approaches that depend on data produced by human experts or advanced models. We anticipate that this work will open new avenues for self-improvement techniques in long-context scenarios, which are essential for the continual advancement of LLMs.

https://huggingface.co/discussions/paper/673593ef8d2bfc6159c2f9f6