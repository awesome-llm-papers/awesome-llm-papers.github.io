---
layout: publication
title: Ovis-u1 Technical Report
authors: Guo-hua Wang, Shanshan Zhao, Xinjie Zhang, Liangfu Cao, Pengxin Zhan, Lunhao
  Duan, Shiyin Lu, Minghao Fu, Xiaohao Chen, Jianshan Zhao, Yang Li, Qing-guo Chen
conference: No Venue
year: 2025
bibkey: wang2025ovis
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/686347cd588cea0da970c886'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.23044'}]
tags: ["Evaluation", "Model Architecture", "Training Techniques"]
short_authors: Wang et al.
---
In this report, we introduce Ovis-U1, a 3-billion-parameter unified model that integrates multimodal understanding, text-to-image generation, and image editing capabilities. Building on the foundation of the Ovis series, Ovis-U1 incorporates a diffusion-based visual decoder paired with a bidirectional token refiner, enabling image generation tasks comparable to leading models like GPT-4o. Unlike some previous models that use a frozen MLLM for generation tasks, Ovis-U1 utilizes a new unified training approach starting from a language model. Compared to training solely on understanding or generation tasks, unified training yields better performance, demonstrating the enhancement achieved by integrating these two tasks. Ovis-U1 achieves a score of 69.6 on the OpenCompass Multi-modal Academic Benchmark, surpassing recent state-of-the-art models such as Ristretto-3B and SAIL-VL-1.5-2B. In text-to-image generation, it excels with scores of 83.72 and 0.89 on the DPG-Bench and GenEval benchmarks, respectively. For image editing, it achieves 4.00 and 6.42 on the ImgEdit-Bench and GEdit-Bench-EN, respectively. As the initial version of the Ovis unified model series, Ovis-U1 pushes the boundaries of multimodal understanding, generation, and editing.

https://huggingface.co/discussions/paper/686347cd588cea0da970c886