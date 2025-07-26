---
layout: publication
title: Deliberation In Latent Space Via Differentiable Cache Augmentation
authors: Luyang Liu, Jonas Pfeiffer, Jiaxing Wu, Jun Xie, Arthur Szlam
conference: No Venue
year: 2024
bibkey: liu2024deliberation
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/676a3ec1b91a321e164a87ca'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2412.17747'}]
tags: ["Memory & Context", "Training Techniques"]
short_authors: Liu et al.
---
Techniques enabling large language models (LLMs) to "think more" by generating and attending to intermediate reasoning steps have shown promise in solving complex problems. However, the standard approaches generate sequences of discrete tokens immediately before responding, and so they can incur significant latency costs and be challenging to optimize. In this work, we demonstrate that a frozen LLM can be augmented with an offline coprocessor that operates on the model's key-value (kv) cache. This coprocessor augments the cache with a set of latent embeddings designed to improve the fidelity of subsequent decoding. We train this coprocessor using the language modeling loss from the decoder on standard pretraining data, while keeping the decoder itself frozen. This approach enables the model to learn, in an end-to-end differentiable fashion, how to distill additional computation into its kv-cache. Because the decoder remains unchanged, the coprocessor can operate offline and asynchronously, and the language model can function normally if the coprocessor is unavailable or if a given cache is deemed not to require extra computation. We show experimentally that when a cache is augmented, the decoder achieves lower perplexity on numerous subsequent tokens. Furthermore, even without any task-specific training, our experiments demonstrate that cache augmentation consistently reduces perplexity and improves performance across a range of reasoning-intensive tasks.

https://huggingface.co/discussions/paper/676a3ec1b91a321e164a87ca