---
layout: publication
title: 'Infinitehip: Extending Language Model Context Up To 3 Million Tokens On A
  Single GPU'
authors: Heejun Lee, Geon Park, Jaduk Suh, Sung Ju Hwang
conference: No Venue
year: 2025
bibkey: lee2025infinitehip
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.08910'}]
tags: ["Memory & Context"]
short_authors: Lee et al.
---
In modern large language models (LLMs), handling very long context lengths presents significant challenges as it causes slower inference speeds and increased memory costs. Additionally, most existing pre-trained LLMs fail to generalize beyond their original training sequence lengths. To enable efficient and practical long-context utilization, we introduce InfiniteHiP, a novel, and practical LLM inference framework that accelerates processing by dynamically eliminating irrelevant context tokens through a modular hierarchical token pruning algorithm. Our method also allows generalization to longer sequences by selectively applying various RoPE adjustment methods according to the internal attention patterns within LLMs. Furthermore, we offload the key-value cache to host memory during inference, significantly reducing GPU memory pressure. As a result, InfiniteHiP enables the processing of up to 3 million tokens on a single L40s 48GB GPU -- 3x larger -- without any permanent loss of context information. Our framework achieves an 18.95x speedup in attention decoding for a 1 million token context without requiring additional training. We implement our method in the SGLang framework and demonstrate its effectiveness and practicality through extensive evaluations.

https://huggingface.co/discussions/paper/67aebd4a225614bbe7f6f2d6