---
layout: publication
title: 'Moe-llava: Mixture Of Experts For Large Vision-language Models'
authors: Bin Lin, Zhenyu Tang, Yang Ye, Jiaxi Cui, Bin Zhu, Peng Jin, Junwu Zhang,
  Munan Ning, Li Yuan
conference: No Venue
year: 2024
bibkey: lin2024moe
additional_links: [{name: Code, url: 'https://github.com/PKU-YuanGroup/MoE-LLaVA'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/65b86b41e0bde92c1761c655'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2401.15947'}]
tags: ["Model Architecture"]
short_authors: Lin et al.
---
For Large Vision-Language Models (LVLMs), scaling the model can effectively improve performance. However, expanding model parameters significantly increases the training and inferring costs, as all model parameters are activated for each token in the calculation. In this work, we propose a novel training strategy MoE-tuning for LVLMs, which can constructing a sparse model with an outrageous number of parameter but a constant computational cost, and effectively addresses the performance degradation typically associated with multi-modal learning and model sparsity. Furthermore, we present the MoE-LLaVA framework, a MoE-based sparse LVLM architecture. This framework uniquely activates only the top-k experts through routers during deployment, keeping the remaining experts inactive. Our extensive experiments highlight the excellent capabilities of MoE-LLaVA in visual understanding and its potential to reduce hallucinations in model outputs. Remarkably, with just 3 billion sparsely activated parameters, MoE-LLaVA demonstrates performance comparable to the LLaVA-1.5-7B on various visual understanding datasets and even surpasses the LLaVA-1.5-13B in object hallucination benchmarks. Through MoE-LLaVA, we aim to establish a baseline for sparse LVLMs and provide valuable insights for future research in developing more efficient and effective multi-modal learning systems. Code is released at https://github.com/PKU-YuanGroup/MoE-LLaVA.

https://huggingface.co/discussions/paper/65b86b41e0bde92c1761c655