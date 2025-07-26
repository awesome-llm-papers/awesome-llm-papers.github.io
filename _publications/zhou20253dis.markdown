---
layout: publication
title: '3DIS-FLUX: Simple And Efficient Multi-instance Generation With Dit Rendering'
authors: Dewei Zhou, Ji Xie, Zongxin Yang, Yi Yang
conference: No Venue
year: 2025
bibkey: zhou20253dis
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.05131'}]
tags: ["Has Code", "Model Architecture", "Tools", "Training Techniques"]
short_authors: Zhou et al.
---
The growing demand for controllable outputs in text-to-image generation has driven significant advancements in multi-instance generation (MIG), enabling users to define both instance layouts and attributes. Currently, the state-of-the-art methods in MIG are primarily adapter-based. However, these methods necessitate retraining a new adapter each time a more advanced model is released, resulting in significant resource consumption. A methodology named Depth-Driven Decoupled Instance Synthesis (3DIS) has been introduced, which decouples MIG into two distinct phases: 1) depth-based scene construction and 2) detail rendering with widely pre-trained depth control models. The 3DIS method requires adapter training solely during the scene construction phase, while enabling various models to perform training-free detail rendering. Initially, 3DIS focused on rendering techniques utilizing U-Net architectures such as SD1.5, SD2, and SDXL, without exploring the potential of recent DiT-based models like FLUX. In this paper, we present 3DIS-FLUX, an extension of the 3DIS framework that integrates the FLUX model for enhanced rendering capabilities. Specifically, we employ the FLUX.1-Depth-dev model for depth map controlled image generation and introduce a detail renderer that manipulates the Attention Mask in FLUX's Joint Attention mechanism based on layout information. This approach allows for the precise rendering of fine-grained attributes of each instance. Our experimental results indicate that 3DIS-FLUX, leveraging the FLUX model, outperforms the original 3DIS method, which utilized SD2 and SDXL, and surpasses current state-of-the-art adapter-based methods in terms of both performance and image quality. Project Page: https://limuloo.github.io/3DIS/.

https://huggingface.co/discussions/paper/678739a71f65db189f9e7629