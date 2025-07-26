---
layout: publication
title: 'Langsplatv2: High-dimensional 3D Language Gaussian Splatting With 450+ FPS'
authors: Wanhua Li, Yujie Zhao, Minghan Qin, Yang Liu, Yuanhao Cai, Chuang Gan, Hanspeter
  Pfister
conference: No Venue
year: 2025
bibkey: li2025langsplatv2
additional_links: [{name: Code, url: 'https://langsplat-v2.github.io'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/68708cbac8391850d6097896'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2507.07136'}]
tags: ["Efficiency", "Has Code"]
short_authors: Li et al.
---
In this paper, we introduce LangSplatV2, which achieves high-dimensional feature splatting at 476.2 FPS and 3D open-vocabulary text querying at 384.6 FPS for high-resolution images, providing a 42 times speedup and a 47 times boost over LangSplat respectively, along with improved query accuracy. LangSplat employs Gaussian Splatting to embed 2D CLIP language features into 3D, significantly enhancing speed and learning a precise 3D language field with SAM semantics. Such advancements in 3D language fields are crucial for applications that require language interaction within complex scenes. However, LangSplat does not yet achieve real-time inference performance (8.2 FPS), even with advanced A100 GPUs, severely limiting its broader application. In this paper, we first conduct a detailed time analysis of LangSplat, identifying the heavyweight decoder as the primary speed bottleneck. Our solution, LangSplatV2 assumes that each Gaussian acts as a sparse code within a global dictionary, leading to the learning of a 3D sparse coefficient field that entirely eliminates the need for a heavyweight decoder. By leveraging this sparsity, we further propose an efficient sparse coefficient splatting method with CUDA optimization, rendering high-dimensional feature maps at high quality while incurring only the time cost of splatting an ultra-low-dimensional feature. Our experimental results demonstrate that LangSplatV2 not only achieves better or competitive query accuracy but is also significantly faster. Codes and demos are available at our project page: https://langsplat-v2.github.io.

https://huggingface.co/discussions/paper/68708cbac8391850d6097896