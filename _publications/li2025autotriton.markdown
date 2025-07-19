---
layout: publication
title: 'Autotriton: Automatic Triton Programming With Reinforcement Learning In Llms'
authors: Li et al.
conference: Artificial Intelligence
year: 2025
bibkey: li2025autotriton
citations: 289
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2507.05687'}]
tags: [Training Techniques, Alt, Agentic, Evaluation, IJCAI, Efficiency And Optimization,
  AISTATS, Reinforcement Learning, Fine Tuning, UAI, AAAI]
---
Kernel development in deep learning requires optimizing computational units across hardware while balancing memory management, parallelism, and hardware-specific optimizations through extensive empirical tuning. Although domain-specific languages like Triton simplify GPU programming by abstracting low-level details, developers must still manually tune critical parameters such as tile sizes and memory access patterns through iterative experimentation, creating substantial barriers to optimal performance and wider adoption. In this work, we introduce AutoTriton, the first model dedicated to Triton programming powered by reinforcement learning (RL). AutoTriton performs supervised fine-tuning (SFT) to be equipped with essential Triton programming expertise using a high-quality data gathering pipeline, and conducts RL with Group Relative Policy Optimization (GRPO) algorithm, combining a rule-based reward and an execution-based reward to further improve Triton programming ability, sequentially. Experiments across five evaluation channels of TritonBench and KernelBench illustrate that our 8B model AutoTriton achieves performance comparable to mainstream large models, including Claude-4-Sonnet and DeepSeek-R1-0528. Further experimental analysis demonstrates the crucial role of each module within AutoTriton, including the SFT stage, the RL stage, and the reward design strategy. These findings underscore the promise of RL for automatically generating high-performance kernels, and since high-performance kernels are core components of AI systems, this breakthrough establishes an important foundation for building more efficient AI systems. The model and code will be available at https://github.com/AI9Stars/AutoTriton.