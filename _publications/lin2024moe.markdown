---
layout: publication
title: 'Moe-llava: Mixture Of Experts For Large Vision-language Models'
authors: Bin Lin et al.
conference: Arxiv
year: 2024
citations: 18
bibkey: lin2024moe
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2401.15947'}, {name: Code,
    url: 'https://github.com/PKU-YuanGroup/MoE-LLaVA'}]
tags: [Has Code, Model Architecture, RAG, Multimodal Models, Training Techniques,
  Evaluation]
---
Recent advances demonstrate that scaling Large Vision-Language Models (LVLMs)
effectively improves downstream task performances. However, existing scaling
methods enable all model parameters to be active for each token in the
calculation, which brings massive training and inferring costs. In this work,
we propose a simple yet effective training strategy MoE-Tuning for LVLMs. This
strategy innovatively addresses the common issue of performance degradation in
multi-modal sparsity learning, consequently constructing a sparse model with an
outrageous number of parameters but a constant computational cost. Furthermore,
we present the MoE-LLaVA, a MoE-based sparse LVLM architecture, which uniquely
activates only the top-k experts through routers during deployment, keeping the
remaining experts inactive. Extensive experiments show the significant
performance of MoE-LLaVA in a variety of visual understanding and object
hallucination benchmarks. Remarkably, with only approximately 3B sparsely
activated parameters, MoE-LLaVA demonstrates performance comparable to the
LLaVA-1.5-7B on various visual understanding datasets and even surpasses the
LLaVA-1.5-13B in object hallucination benchmark. Through MoE-LLaVA, we aim to
establish a baseline for sparse LVLMs and provide valuable insights for future
research in developing more efficient and effective multi-modal learning
systems. Code is released at https://github.com/PKU-YuanGroup/MoE-LLaVA.