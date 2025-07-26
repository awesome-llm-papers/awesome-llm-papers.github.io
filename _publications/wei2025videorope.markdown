---
layout: publication
title: 'Videorope: What Makes For Good Video Rotary Position Embedding?'
authors: Xilin Wei, Xiaoran Liu, Yuhang Zang, Xiaoyi Dong, Pan Zhang, Yuhang Cao,
  Jian Tong, Haodong Duan, Qipeng Guo, Jiaqi Wang, Xipeng Qiu, Dahua Lin
conference: No Venue
year: 2025
bibkey: wei2025videorope
additional_links: [{name: Code, url: 'https://github.com/Wiselnn570/VideoRoPE\{https://github.com/Wiselnn570/VideoRoPE\'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67a97a4a174028234b74f707'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.05173'}]
tags: ["Has Code"]
short_authors: Wei et al.
---
While Rotary Position Embedding (RoPE) and its variants are widely adopted for their long-context capabilities, the extension of the 1D RoPE to video, with its complex spatio-temporal structure, remains an open challenge. This work first introduces a comprehensive analysis that identifies four key characteristics essential for the effective adaptation of RoPE to video, which have not been fully considered in prior work. As part of our analysis, we introduce a challenging V-NIAH-D (Visual Needle-In-A-Haystack with Distractors) task, which adds periodic distractors into V-NIAH. The V-NIAH-D task demonstrates that previous RoPE variants, lacking appropriate temporal dimension allocation, are easily misled by distractors. Based on our analysis, we introduce VideoRoPE, with a 3D structure designed to preserve spatio-temporal relationships. VideoRoPE features low-frequency temporal allocation to mitigate periodic oscillations, a diagonal layout to maintain spatial symmetry, and adjustable temporal spacing to decouple temporal and spatial indexing. VideoRoPE consistently surpasses previous RoPE variants, across diverse downstream tasks such as long video retrieval, video understanding, and video hallucination. Our code will be available at https://github.com/Wiselnn570/VideoRoPE\{https://github.com/Wiselnn570/VideoRoPE\}.

https://huggingface.co/discussions/paper/67a97a4a174028234b74f707