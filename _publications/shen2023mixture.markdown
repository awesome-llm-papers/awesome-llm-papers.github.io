---
layout: publication
title: Mixture-of-experts Meets Instruction Tuning:a Winning Combination For Large
  Language Models
authors: Sheng Shen et al.
conference: Arxiv
year: 2023
citations: 15
bibkey: shen2023mixture
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.14705'}]
tags: [Few-Shot, Tools, Model Architecture, Training Techniques]
---
Sparse Mixture-of-Experts (MoE) is a neural architecture design that can be
utilized to add learnable parameters to Large Language Models (LLMs) without
increasing inference cost. Instruction tuning is a technique for training LLMs
to follow instructions. We advocate combining these two approaches, as we find
that MoE models benefit more from instruction tuning than dense models. In
particular, we conduct empirical studies across three experimental setups: (i)
Direct finetuning on individual downstream tasks devoid of instruction tuning;
(ii) Instructiontuning followed by in-context few-shot or zero-shot
generalization on downstream tasks; and (iii) Instruction tuning supplemented
by further finetuning on individual downstream tasks. In the first scenario,
MoE models overall underperform dense models of identical computational
capacity. This narrative, however, dramatically changes with the introduction
of instruction tuning (second and third scenario), used independently or in
conjunction with task-specific finetuning. Our most powerful model,
FLAN-MOE-32B, surpasses the performance of FLAN-PALM-62B on four benchmark
tasks, while using only a third of the FLOPs. The advancements embodied
byFLAN-MOE inspire a reevaluation of the design principles of large-scale,
high-performance language models in the framework of task-agnostic learning.