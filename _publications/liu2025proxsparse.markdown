---
layout: publication
title: 'Proxsparse: Regularized Learning Of Semi-structured Sparsity Masks For Pretrained
  Llms'
authors: Liu et al.
conference: Pattern Recognition
year: 2025
bibkey: liu2025proxsparse
citations: 94
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.00258'}]
tags: [RAG, Tools, Evaluation, CVPR, Efficiency And Optimization, Fine Tuning, Pruning]
---
Large Language Models (LLMs) have demonstrated exceptional performance in natural language processing tasks, yet their massive size makes serving them inefficient and costly. Semi-structured pruning has emerged as an effective method for model acceleration, but existing approaches are suboptimal because they focus on local, layer-wise optimizations using heuristic rules, failing to leverage global feedback. We present ProxSparse, a learning-based framework for mask selection enabled by regularized optimization. ProxSparse transforms the rigid, non-differentiable mask selection process into a smoother optimization procedure, allowing gradual mask exploration with flexibility. ProxSparse does not involve additional weight updates once the mask is determined. Our extensive evaluations on 7 widely used models show that ProxSparse consistently outperforms previously proposed semi-structured mask selection methods with significant improvement, demonstrating the effectiveness of our learned approach towards semi-structured pruning.