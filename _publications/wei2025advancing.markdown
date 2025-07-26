---
layout: publication
title: Advancing Multimodal Reasoning Via Reinforcement Learning With Cold Start
authors: Lai Wei, Yuting Li, Kaipeng Zheng, Chen Wang, Yue Wang, Linghe Kong, Lichao
  Sun, Weiran Huang
conference: No Venue
year: 2025
bibkey: wei2025advancing
additional_links: [{name: Code, url: 'https://github.com/waltonfuture/RL-with-Cold-Start'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/6837c363b127cae8a0b36f6f'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.22334'}]
tags: ["Reinforcement Learning"]
short_authors: Wei et al.
---
Recent advancements in large language models (LLMs) have demonstrated impressive chain-of-thought reasoning capabilities, with reinforcement learning (RL) playing a crucial role in this progress. While "aha moment" patterns--where models exhibit self-correction through reflection--are often attributed to emergent properties from RL, we first demonstrate that these patterns exist in multimodal LLMs (MLLMs) prior to RL training but may not necessarily correlate with improved reasoning performance. Building on these insights, we present a comprehensive study on enhancing multimodal reasoning through a two-stage approach: (1) supervised fine-tuning (SFT) as a cold start with structured chain-of-thought reasoning patterns, followed by (2) reinforcement learning via GRPO to further refine these capabilities. Our extensive experiments show that this combined approach consistently outperforms both SFT-only and RL-only methods across challenging multimodal reasoning benchmarks. The resulting models achieve state-of-the-art performance among open-source MLLMs at both 3B and 7B scales, with our 7B model showing substantial improvements over base models (e.g., 66.3 %rightarrow73.4 % on MathVista, 62.9 %rightarrow70.4 % on We-Math) and our 3B model achieving performance competitive with several 7B models. Overall, this work provides practical guidance for building advanced multimodal reasoning models. Our code is available at https://github.com/waltonfuture/RL-with-Cold-Start.

https://huggingface.co/discussions/paper/6837c363b127cae8a0b36f6f