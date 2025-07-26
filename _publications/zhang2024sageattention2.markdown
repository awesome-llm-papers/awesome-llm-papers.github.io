---
layout: publication
title: 'Sageattention2 Technical Report: Accurate 4 Bit Attention For Plug-and-play
  Inference Acceleration'
authors: Jintao Zhang, Haofeng Huang, Pengle Zhang, Jia Wei, Jun Zhu, Jianfei Chen
conference: No Venue
year: 2024
bibkey: zhang2024sageattention2
additional_links: [{name: Code, url: 'https://github.com/thu-ml/SageAttention'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/673ea5042671f1feac00b792'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2411.10958'}]
tags: ["Efficiency", "Has Code"]
short_authors: Zhang et al.
---
Although quantization for linear layers has been widely used, its application to accelerate the attention process remains limited. SageAttention utilizes 8-bit matrix multiplication, 16-bit matrix multiplication with 16-bit accumulator, and precision-enhancing methods, implementing an accurate and 2x speedup kernel compared to FlashAttention2. To further enhance the efficiency of attention computation while maintaining precision, we propose SageAttention2, which utilizes significantly faster 4-bit matrix multiplication (Matmul) alongside additional precision-enhancing techniques. First, we propose to quantize matrixes (Q, K) to INT4 in a warp-level granularity and quantize matrixes (widetilde P, V) to FP8. Second, we propose a method to smooth Q and V, enhancing the accuracy of attention with INT4 QK and FP8 PV. Third, we analyze the quantization accuracy across timesteps and layers, then propose an adaptive quantization method to ensure the end-to-end metrics over various models. The operations per second (OPS) of SageAttention2 surpass FlashAttention2 and xformers by about 3x and 5x on RTX4090, respectively. Comprehensive experiments confirm that our approach incurs negligible end-to-end metrics loss across diverse models, including those for large language processing, image generation, and video generation. The codes are available at https://github.com/thu-ml/SageAttention.

https://huggingface.co/discussions/paper/673ea5042671f1feac00b792