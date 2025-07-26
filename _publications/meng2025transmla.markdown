---
layout: publication
title: 'Transmla: Multi-head Latent Attention Is All You Need'
authors: Fanxu Meng, Zengwei Yao, Muhan Zhang
conference: No Venue
year: 2025
bibkey: meng2025transmla
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.07864'}]
tags: ["Memory & Context"]
short_authors: Fanxu Meng, Zengwei Yao, Muhan Zhang
---
Modern large language models (LLMs) often encounter communication bottlenecks on current hardware, rather than purely computational constraints. Multi-head Latent Attention (MLA) tackles this challenge by using low-rank matrices in the key-value (KV) layers, thereby allowing compressed latent KV states to be cached. This approach significantly reduces the KV cache size relative to traditional multi-head attention, leading to faster inference. Moreover, MLA employs an up-projection matrix to increase expressiveness, trading additional computation for reduced communication overhead. Although MLA has demonstrated efficiency and effectiveness in Deepseek V2/V3/R1, many major model providers still rely on Group Query Attention (GQA) and have not announced any plans to adopt MLA. In this paper, we show that GQA can always be represented by MLA while maintaining the same KV cache overhead, but the converse does not hold. To encourage broader use of MLA, we introduce **TransMLA**, a post-training method that converts widely used GQA-based pre-trained models (e.g., LLaMA, Qwen, Mixtral) into MLA-based models. After conversion, the model can undergo additional training to boost expressiveness without increasing the KV cache size. Furthermore, we plan to develop MLA-specific inference acceleration techniques to preserve low latency in transformed models, thus enabling more efficient distillation of Deepseek R1.

https://huggingface.co/discussions/paper/67ad5b3b007d78b391946a79