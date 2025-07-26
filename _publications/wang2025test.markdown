---
layout: publication
title: Test-time Scaling With Reflective Generative Model
authors: Zixiao Wang, Yuxin Wang, Xiaorui Wang, Mengting Xing, Jie Gao, Jianjun Xu,
  Guangcan Liu, Chenhui Jin, Zhuo Wang, Shengzhuo Zhang, Hongtao Xie
conference: No Venue
year: 2025
bibkey: wang2025test
additional_links: [{name: Code, url: 'https://github.com/MetaStone-AI/MetaStone-S1'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2507.01951'}]
tags: ["Has Code"]
short_authors: Wang et al.
---
We introduce our first reflective generative model MetaStone-S1, which obtains OpenAI o3's performance via the self-supervised process reward model (SPRM). Through sharing the backbone network and using task-specific heads for next token prediction and process scoring respectively, SPRM successfully integrates the policy model and process reward model(PRM) into a unified interface without extra process annotation, reducing over 99% PRM parameters for efficient reasoning. Equipped with SPRM, MetaStone-S1 is naturally suitable for test time scaling (TTS), and we provide three reasoning effort modes (low, medium, and high), based on the controllable thinking length. Moreover, we empirically establish a scaling law that reveals the relationship between total thinking computation and TTS performance. Experiments demonstrate that our MetaStone-S1 achieves comparable performance to OpenAI-o3-mini's series with only 32B parameter size. To support the research community, we have open-sourced MetaStone-S1 at https://github.com/MetaStone-AI/MetaStone-S1.

https://huggingface.co/discussions/paper/6868daac213f123a1f88b9d3