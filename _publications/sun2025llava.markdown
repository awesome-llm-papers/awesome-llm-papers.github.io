---
layout: publication
title: 'Llava-scissor: Token Compression With Semantic Connected Components For Video
  Llms'
authors: Boyuan Sun, Jiaxing Zhao, Xihan Wei, Qibin Hou
conference: No Venue
year: 2025
bibkey: sun2025llava
additional_links: [{name: Code, url: 'https://github.com/HumanMLLM/LLaVA-Scissor'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.21862'}]
tags: ["Has Code"]
short_authors: Sun et al.
---
In this paper, we present LLaVA-Scissor, a training-free token compression strategy designed for video multimodal large language models. Previous methods mostly attempt to compress tokens based on attention scores, but fail to effectively capture all semantic regions and often lead to token redundancy. Differently, we propose to leverage the Semantic Connected Components (SCC) approach that assigns tokens to distinct semantic regions within the token set, ensuring comprehensive semantic coverage. The outcome is a two-step spatio-temporal token compression strategy that utilizes SCC in both spatial and temporal domains. This strategy can effectively compress tokens by representing the entire video with a set of non-overlapping semantic tokens. We conduct extensive evaluations of the token compression capabilities of LLaVA-Scissor across diverse video understanding benchmarks, including video question answering, long video understanding, and comprehensive multi-choices benchmarks. Experimental results show that the proposed LLaVA-Scissor outperforms other token compression methods, achieving superior performance in various video understanding benchmarks, particularly at low token retention ratios. Project page: https://github.com/HumanMLLM/LLaVA-Scissor.

https://huggingface.co/discussions/paper/6861eea89e7509383d29ab33