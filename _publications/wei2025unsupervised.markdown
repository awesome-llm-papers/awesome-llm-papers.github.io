---
layout: publication
title: Unsupervised Post-training For Multi-modal LLM Reasoning Via GRPO
authors: Lai Wei, Yuting Li, Chen Wang, Yue Wang, Linghe Kong, Weiran Huang, Lichao
  Sun
conference: No Venue
year: 2025
bibkey: wei2025unsupervised
additional_links: [{name: Code, url: 'https://github.com/waltonfuture/MM-UPT'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/6837c318a4e378954486e48a'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.22453'}]
tags: ["Has Code"]
short_authors: Wei et al.
---
Improving Multi-modal Large Language Models (MLLMs) in the post-training stage typically relies on supervised fine-tuning (SFT) or reinforcement learning (RL). However, these supervised methods require expensive and manually annotated multi-modal data--an ultimately unsustainable resource. While recent efforts have explored unsupervised post-training, their methods are complex and difficult to iterate. In this work, we are the first to investigate the use of GRPO, a stable and scalable online RL algorithm, for enabling continual self-improvement without any external supervision. We propose MM-UPT, a simple yet effective framework for unsupervised post-training of MLLMs. MM-UPT builds upon GRPO, replacing traditional reward signals with a self-rewarding mechanism based on majority voting over multiple sampled responses. Our experiments demonstrate that MM-UPT significantly improves the reasoning ability of Qwen2.5-VL-7B (e.g., 66.3 %rightarrow72.9 % on MathVista, 62.9 %rightarrow68.7 % on We-Math), using standard dataset without ground truth labels. MM-UPT also outperforms prior unsupervised baselines and even approaches the results of supervised GRPO. Furthermore, we show that incorporating synthetic questions, generated solely by MLLM itself, can boost performance as well, highlighting a promising approach for scalable self-improvement. Overall, MM-UPT offers a new paradigm for continual, autonomous enhancement of MLLMs in the absence of external supervision. Our code is available at https://github.com/waltonfuture/MM-UPT.

https://huggingface.co/discussions/paper/6837c318a4e378954486e48a