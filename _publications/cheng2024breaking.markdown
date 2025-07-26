---
layout: publication
title: 'Breaking The Memory Barrier: Near Infinite Batch Size Scaling For Contrastive
  Loss'
authors: Zesen Cheng, Hang Zhang, Kehan Li, Sicong Leng, Zhiqiang Hu, Fei Wu, Deli
  Zhao, Xin Li, Lidong Bing
conference: No Venue
year: 2024
bibkey: cheng2024breaking
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/671b005126d87414f5a615f4'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2410.17243'}]
tags: ["Training Techniques"]
short_authors: Cheng et al.
---
Contrastive loss is a powerful approach for representation learning, where larger batch sizes enhance performance by providing more negative samples to better distinguish between similar and dissimilar data. However, scaling batch sizes is constrained by the quadratic growth in GPU memory consumption, primarily due to the full instantiation of the similarity matrix. To address this, we propose a tile-based computation strategy that partitions the contrastive loss calculation into arbitrary small blocks, avoiding full materialization of the similarity matrix. Furthermore, we introduce a multi-level tiling strategy to leverage the hierarchical structure of distributed systems, employing ring-based communication at the GPU level to optimize synchronization and fused kernels at the CUDA core level to reduce I/O overhead. Experimental results show that the proposed method scales batch sizes to unprecedented levels. For instance, it enables contrastive training of a CLIP-ViT-L/14 model with a batch size of 4M or 12M using 8 or 32 A800 80GB without sacrificing any accuracy. Compared to SOTA memory-efficient solutions, it achieves a two-order-of-magnitude reduction in memory while maintaining comparable speed. The code will be made publicly available.

https://huggingface.co/discussions/paper/671b005126d87414f5a615f4