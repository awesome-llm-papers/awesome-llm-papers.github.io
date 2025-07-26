---
layout: publication
title: 'Sageattention3: Microscaling FP4 Attention For Inference And An Exploration
  Of 8-bit Training'
authors: Jintao Zhang, Jia Wei, Pengle Zhang, Xiaoming Xu, Haofeng Huang, Haoxu Wang,
  Kai Jiang, Jun Zhu, Jianfei Chen
conference: No Venue
year: 2025
bibkey: zhang2025sageattention3
additional_links: [{name: Code, url: 'https://github.com/thu-ml/SageAttention'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/682d426551ce04237318d0b9'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.11594'}]
tags: ["Efficiency", "Has Code"]
short_authors: Zhang et al.
---
The efficiency of attention is important due to its quadratic time complexity. We enhance the efficiency of attention through two key contributions: First, we leverage the new FP4 Tensor Cores in Blackwell GPUs to accelerate attention computation. Our implementation achieves 1038 TOPS on RTX5090, which is a 5x speedup over the fastest FlashAttention on RTX5090. Experiments show that our FP4 attention can accelerate inference of various models in a plug-and-play way. Second, we pioneer low-bit attention to training tasks. Existing low-bit attention works like FlashAttention3 and SageAttention focus only on inference. However, the efficiency of training large models is also important. To explore whether low-bit attention can be effectively applied to training tasks, we design an accurate and efficient 8-bit attention for both forward and backward propagation. Experiments indicate that 8-bit attention achieves lossless performance in fine-tuning tasks but exhibits slower convergence in pretraining tasks. The code will be available at https://github.com/thu-ml/SageAttention.

https://huggingface.co/discussions/paper/682d426551ce04237318d0b9