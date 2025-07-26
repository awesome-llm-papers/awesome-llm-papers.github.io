---
layout: publication
title: 'Hogwild! Inference: Parallel LLM Generation Via Concurrent Attention'
authors: Gleb Rodionov, Roman Garipov, Alina Shutova, George Yakushev, Vage Egiazarian,
  Anton Sinitsin, Denis Kuznedelev, Dan Alistarh
conference: No Venue
year: 2025
bibkey: rodionov2025hogwild
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.06261'}]
tags: ["Memory & Context"]
short_authors: Rodionov et al.
---
Large Language Models (LLMs) have demonstrated the ability to tackle increasingly complex tasks through advanced reasoning, long-form content generation, and tool use. Solving these tasks often involves long inference-time computations. In human problem solving, a common strategy to expedite work is collaboration: by dividing the problem into sub-tasks, exploring different strategies concurrently, etc. Recent research has shown that LLMs can also operate in parallel by implementing explicit cooperation frameworks, such as voting mechanisms or the explicit creation of independent sub-tasks that can be executed in parallel. However, each of these frameworks may not be suitable for all types of tasks, which can hinder their applicability. In this work, we propose a different design approach: we run LLM "workers" in parallel , allowing them to synchronize via a concurrently-updated attention cache and prompt these workers to decide how best to collaborate. Our approach allows the instances to come up with their own collaboration strategy for the problem at hand, all the while "seeing" each other's partial progress in the concurrent cache. We implement this approach via Hogwild! Inference: a parallel LLM inference engine where multiple instances of the same LLM run in parallel with the same attention cache, with "instant" access to each other's generated tokens. Hogwild! inference takes advantage of Rotary Position Embeddings (RoPE) to avoid recomputation while improving parallel hardware utilization. We find that modern reasoning-capable LLMs can perform inference with shared Key-Value cache out of the box, without additional fine-tuning.

https://huggingface.co/discussions/paper/67f60df3d0df7eccaae93eff