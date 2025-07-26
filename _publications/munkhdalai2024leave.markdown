---
layout: publication
title: 'Leave No Context Behind: Efficient Infinite Context Transformers With Infini-attention'
authors: Tsendsuren Munkhdalai, Manaal Faruqui, Siddharth Gopal
conference: No Venue
year: 2024
bibkey: munkhdalai2024leave
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2404.07143'}]
tags: ["Model Architecture"]
short_authors: Tsendsuren Munkhdalai, Manaal Faruqui, Siddharth Gopal
---
This work introduces an efficient method to scale Transformer-based Large Language Models (LLMs) to infinitely long inputs with bounded memory and computation. A key component in our proposed approach is a new attention technique dubbed Infini-attention. The Infini-attention incorporates a compressive memory into the vanilla attention mechanism and builds in both masked local attention and long-term linear attention mechanisms in a single Transformer block. We demonstrate the effectiveness of our approach on long-context language modeling benchmarks, 1M sequence length passkey context block retrieval and 500K length book summarization tasks with 1B and 8B LLMs. Our approach introduces minimal bounded memory parameters and enables fast streaming inference for LLMs.

https://huggingface.co/discussions/paper/66173d45332ce7fc19839de1