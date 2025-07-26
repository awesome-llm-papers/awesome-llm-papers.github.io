---
layout: publication
title: 'World Modeling Makes A Better Planner: Dual Preference Optimization For Embodied
  Task Planning'
authors: Siyin Wang, Zhaoye Fei, Qinyuan Cheng, Shiduo Zhang, Panpan Cai, Jinlan Fu,
  Xipeng Qiu
conference: No Venue
year: 2025
bibkey: wang2025world
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.10480'}]
tags: ["Efficiency"]
short_authors: Wang et al.
---
Recent advances in large vision-language models (LVLMs) have shown promise for embodied task planning, yet they struggle with fundamental challenges like dependency constraints and efficiency. Existing approaches either solely optimize action selection or leverage world models during inference, overlooking the benefits of learning to model the world as a way to enhance planning capabilities. We propose Dual Preference Optimization (D^2PO), a new learning framework that jointly optimizes state prediction and action selection through preference learning, enabling LVLMs to understand environment dynamics for better planning. To automatically collect trajectories and stepwise preference data without human annotation, we introduce a tree search mechanism for extensive exploration via trial-and-error. Extensive experiments on VoTa-Bench demonstrate that our D^2PO-based method significantly outperforms existing methods and GPT-4o when applied to Qwen2-VL (7B), LLaVA-1.6 (7B), and LLaMA-3.2 (11B), achieving superior task success rates with more efficient execution paths.

https://huggingface.co/discussions/paper/67d38a44d3d16e1166d81c54