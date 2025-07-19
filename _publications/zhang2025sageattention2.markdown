---
layout: publication
title: 'Sageattention2++: A More Efficient Implementation Of Sageattention2'
authors: Zhang et al.
conference: Lecture Notes in Computer Science
year: 2025
bibkey: zhang2025sageattention2
citations: 91
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.21136'}]
tags: [Attention Mechanism, Evaluation, Model Architecture, Efficiency And Optimization,
  Quantization]
---
The efficiency of attention is critical because its time complexity grows quadratically with sequence length. SageAttention2 addresses this by utilizing quantization to accelerate matrix multiplications (Matmul) in attention. To further accelerate SageAttention2, we propose to utilize the faster instruction of FP8 Matmul accumulated in FP16. The instruction is 2x faster than the FP8 Matmul used in SageAttention2. Our experiments show that SageAttention2++ achieves a 3.9x speedup over FlashAttention while maintaining the same attention accuracy as SageAttention2. This means SageAttention2++ effectively accelerates various models, including those for language, image, and video generation, with negligible end-to-end metrics loss. The code will be available at https://github.com/thu-ml/SageAttention.