---
layout: publication
title: What Matters In Transformers? Not All Attention Is Needed
authors: Shwai He, Guoheng Sun, Zheyu Shen, Ang Li
conference: No Venue
year: 2024
bibkey: he2024what
additional_links: [{name: Code, url: 'https://github.com/Shwai-He/LLM-Drop'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/670f43075651052491a76688'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2406.15786'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: He et al.
---
While scaling Transformer-based large language models (LLMs) has demonstrated promising performance across various tasks, it also introduces redundant architectures, posing efficiency challenges for real-world deployment. Despite some recognition of redundancy in LLMs, the variability of redundancy across different architectures in transformers, such as MLP and Attention layers, is under-explored. In this work, we investigate redundancy across different modules within Transformers, including Blocks, MLP, and Attention layers, using a similarity-based metric. Surprisingly, despite the critical role of attention layers in distinguishing transformers from other architectures, we found that a large portion of these layers exhibit excessively high similarity and can be pruned without degrading performance. For instance, Llama-2-70B achieved a 48.4% speedup with only a 2.4% performance drop by pruning half of the attention layers. Furthermore, by tracing model checkpoints throughout the training process, we observed that attention layer redundancy is inherent and consistent across training stages. Additionally, we further propose a method that jointly drops Attention and MLP layers, allowing us to more aggressively drop additional layers. For instance, when dropping 31 layers (Attention + MLP), Llama-2-13B still retains 90% of the performance on the MMLU task. Our work provides valuable insights for future network architecture design. The code is released at: https://github.com/Shwai-He/LLM-Drop.

https://huggingface.co/discussions/paper/670f43075651052491a76688