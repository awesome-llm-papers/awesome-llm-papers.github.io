---
layout: publication
title: Your Mixture-of-experts LLM Is Secretly An Embedding Model For Free
authors: Ziyue Li, Tianyi Zhou
conference: No Venue
year: 2024
bibkey: li2024your
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/670e2ff5ffc411cfa85d300b'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2410.10814'}]
tags: ["Model Architecture"]
short_authors: Ziyue Li, Tianyi Zhou
---
While large language models (LLMs) excel on generation tasks, their decoder-only architecture often limits their potential as embedding models if no further representation finetuning is applied. Does this contradict their claim of generalists? To answer the question, we take a closer look at Mixture-of-Experts (MoE) LLMs. Our study shows that the expert routers in MoE LLMs can serve as an off-the-shelf embedding model with promising performance on a diverse class of embedding-focused tasks, without requiring any finetuning. Moreover, our extensive analysis shows that the MoE routing weights (RW) is complementary to the hidden state (HS) of LLMs, a widely-used embedding. Compared to HS, we find that RW is more robust to the choice of prompts and focuses on high-level semantics. Motivated by the analysis, we propose MoEE combining RW and HS, which achieves better performance than using either separately. Our exploration of their combination and prompting strategy shed several novel insights, e.g., a weighted sum of RW and HS similarities outperforms the similarity on their concatenation. Our experiments are conducted on 6 embedding tasks with 20 datasets from the Massive Text Embedding Benchmark (MTEB). The results demonstrate the significant improvement brought by MoEE to LLM-based embedding without further finetuning.

https://huggingface.co/discussions/paper/670e2ff5ffc411cfa85d300b