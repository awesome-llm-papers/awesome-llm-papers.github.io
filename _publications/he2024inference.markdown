---
layout: publication
title: Inference Performance Optimization For Large Language Models On Cpus
authors: Pujiang He, Shan Zhou, Wenhuan Huang, Changqing Li, Duyi Wang, Bin Guo, Chen
  Meng, Sheng Gui, Weifei Yu, Yi Xie
conference: No Venue
year: 2024
bibkey: he2024inference
additional_links: [{name: Code, url: 'https://github.com/intel/xFasterTransformer'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/668f48825156d55f729b4778'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2407.07304'}]
tags: ["Efficiency", "Memory & Context"]
short_authors: He et al.
---
Large language models (LLMs) have shown exceptional performance and vast potential across diverse tasks. However, the deployment of LLMs with high performance in low-resource environments has garnered significant attention in the industry. When GPU hardware resources are limited, we can explore alternative options on CPUs. To mitigate the financial burden and alleviate constraints imposed by hardware resources, optimizing inference performance is necessary. In this paper, we introduce an easily deployable inference performance optimization solution aimed at accelerating LLMs on CPUs. In this solution, we implement an effective way to reduce the KV cache size while ensuring precision. We propose a distributed inference optimization approach and implement it based on oneAPI Collective Communications Library. Furthermore, we propose optimization approaches for LLMs on CPU, and conduct tailored optimizations for the most commonly used models. The code is open-sourced at https://github.com/intel/xFasterTransformer.

https://huggingface.co/discussions/paper/668f48825156d55f729b4778