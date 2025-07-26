---
layout: publication
title: 'Llama Pro: Progressive Llama With Block Expansion'
authors: Chengyue Wu, Yukang Gan, Yixiao Ge, Zeyu Lu, Jiahao Wang, Ye Feng, Ping Luo,
  Ying Shan
conference: No Venue
year: 2024
bibkey: wu2024llama
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/65978d27b4b5c254cb8b0956'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2401.02415'}]
tags: ["Model Architecture"]
short_authors: Wu et al.
---
Humans generally acquire new skills without compromising the old; however, the opposite holds for Large Language Models (LLMs), e.g., from LLaMA to CodeLLaMA. To this end, we propose a new post-pretraining method for LLMs with an expansion of Transformer blocks. We tune the expanded blocks using only new corpus, efficiently and effectively improving the model's knowledge without catastrophic forgetting. In this paper, we experiment on the corpus of code and math, yielding LLaMA Pro-8.3B, a versatile foundation model initialized from LLaMA2-7B, excelling in general tasks, programming, and mathematics. LLaMA Pro and its instruction-following counterpart (LLaMA Pro-Instruct) achieve advanced performance among various benchmarks, demonstrating superiority over existing open models in the LLaMA family and the immense potential of reasoning and addressing diverse tasks as an intelligent agent. Our findings provide valuable insights into integrating natural and programming languages, laying a solid foundation for developing advanced language agents that operate effectively in various environments.

https://huggingface.co/discussions/paper/65978d27b4b5c254cb8b0956