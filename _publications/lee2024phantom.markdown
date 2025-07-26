---
layout: publication
title: Phantom Of Latent For Large Language And Vision Models
authors: Byung-kwan Lee, Sangyun Chung, Chae Won Kim, Beomchan Park, Yong Man Ro
conference: No Venue
year: 2024
bibkey: lee2024phantom
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2409.14713'}]
tags: ["Efficiency", "Fine-Tuning", "Reinforcement Learning", "Training Techniques"]
short_authors: Lee et al.
---
The success of visual instruction tuning has accelerated the development of large language and vision models (LLVMs). Following the scaling laws of instruction-tuned large language models (LLMs), LLVMs either have further increased their sizes, reaching 26B, 34B, and even 80B parameters. While this increase in model size has yielded significant performance gains, it demands substantially more hardware resources for both training and inference. Consequently, there naturally exists a strong need for efficient LLVMs that achieve the performance of larger models while being smaller in size. To achieve this need, we present a new efficient LLVM family with model sizes of 0.5B, 1.8B, 3.8B, and 7B parameters, Phantom, which significantly enhances learning capabilities within limited structures. By temporarily increasing the latent hidden dimension during multi-head self-attention (MHSA), we make LLVMs prepare to look and understand much more vision-language knowledge on the latent, without substantially increasing physical model sizes. To maximize its advantage, we introduce Phantom Optimization (PO) using both autoregressive supervised fine-tuning (SFT) and direct preference optimization (DPO)-like concept, which effectively follows correct answers while eliminating incorrect and ambiguous ones. Phantom outperforms numerous larger open- and closed-source LLVMs, positioning itself as a leading solution in the landscape of efficient LLVMs.

https://huggingface.co/discussions/paper/66f23c6baef962b23792f191