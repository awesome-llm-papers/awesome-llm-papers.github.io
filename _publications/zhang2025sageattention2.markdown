---
layout: publication
title: 'Sageattention2++: A More Efficient Implementation Of Sageattention2'
authors: Jintao Zhang, Xiaoming Xu, Jia Wei, Haofeng Huang, Pengle Zhang, Chendong
  Xiang, Jun Zhu, Jianfei Chen
conference: No Venue
year: 2025
bibkey: zhang2025sageattention2
additional_links: [{name: Code, url: 'https://github.com/thu-ml/SageAttention'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/6837c923c790885f338b90e5'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.21136'}]
tags: ["Efficiency", "Has Code"]
short_authors: Zhang et al.
---
The efficiency of attention is critical because its time complexity grows quadratically with sequence length. SageAttention2 addresses this by utilizing quantization to accelerate matrix multiplications (Matmul) in attention. To further accelerate SageAttention2, we propose to utilize the faster instruction of FP8 Matmul accumulated in FP16. The instruction is 2x faster than the FP8 Matmul used in SageAttention2. Our experiments show that SageAttention2++ achieves a 3.9x speedup over FlashAttention while maintaining the same attention accuracy as SageAttention2. This means SageAttention2++ effectively accelerates various models, including those for language, image, and video generation, with negligible end-to-end metrics loss. The code will be available at https://github.com/thu-ml/SageAttention.

https://huggingface.co/discussions/paper/6837c923c790885f338b90e5