---
layout: publication
title: 'Paroattention: Pattern-aware Reordering For Efficient Sparse And Quantized
  Attention In Visual Generation Models'
authors: Tianchen Zhao, Ke Hong, Xinhao Yang, Xuefeng Xiao, Huixia Li, Feng Ling,
  Ruiqi Xie, Siqi Chen, Hongyu Zhu, Yichong Zhang, Yu Wang
conference: No Venue
year: 2025
bibkey: zhao2025paroattention
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.16054'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Zhao et al.
---
In visual generation, the quadratic complexity of attention mechanisms results in high memory and computational costs, especially for longer token sequences required in high-resolution image or multi-frame video generation. To address this, prior research has explored techniques such as sparsification and quantization. However, these techniques face significant challenges under low density and reduced bitwidths. Through systematic analysis, we identify that the core difficulty stems from the dispersed and irregular characteristics of visual attention patterns. Therefore, instead of introducing specialized sparsification and quantization design to accommodate such patterns, we propose an alternative strategy: *reorganizing* the attention pattern to alleviate the challenges. Inspired by the local aggregation nature of visual feature extraction, we design a novel **Pattern-Aware token ReOrdering (PARO)** technique, which unifies the diverse attention patterns into a hardware-friendly block-wise pattern. This unification substantially simplifies and enhances both sparsification and quantization. We evaluate the performance-efficiency trade-offs of various design choices and finalize a methodology tailored for the unified pattern. Our approach, **PAROAttention**, achieves video and image generation with lossless metrics, and nearly identical results from full-precision (FP) baselines, while operating at notably lower density (~20%-30%) and bitwidth (**INT8/INT4**), achieving a **1.9x** to **2.7x** end-to-end latency speedup.

https://huggingface.co/discussions/paper/6858e225c0c8e29df8ea3d1a