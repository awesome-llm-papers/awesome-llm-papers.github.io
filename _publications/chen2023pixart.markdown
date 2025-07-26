---
layout: publication
title: "Pixart-\u03B1: Fast Training Of Diffusion Transformer For Photorealistic Text-to-image\
  \ Synthesis"
authors: Junsong Chen, Jincheng Yu, Chongjian Ge, Lewei Yao, Enze Xie1, Yue Wu, Zhongdao
  Wang, James Kwok, Ping Luo, Huchuan Lu, Zhenguo Li
conference: No Venue
year: 2023
bibkey: chen2023pixart
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2310.00426'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Chen et al.
---
The most advanced text-to-image (T2I) models require significant training costs (e.g., millions of GPU hours), seriously hindering the fundamental innovation for the AIGC community while increasing CO2 emissions. This paper introduces PIXART-alpha, a Transformer-based T2I diffusion model whose image generation quality is competitive with state-of-the-art image generators (e.g., Imagen, SDXL, and even Midjourney), reaching near-commercial application standards. Additionally, it supports high-resolution image synthesis up to 1024px resolution with low training cost, as shown in Figure 1 and 2. To achieve this goal, three core designs are proposed: (1) Training strategy decomposition: We devise three distinct training steps that separately optimize pixel dependency, text-image alignment, and image aesthetic quality; (2) Efficient T2I Transformer: We incorporate cross-attention modules into Diffusion Transformer (DiT) to inject text conditions and streamline the computation-intensive class-condition branch; (3) High-informative data: We emphasize the significance of concept density in text-image pairs and leverage a large Vision-Language model to auto-label dense pseudo-captions to assist text-image alignment learning. As a result, PIXART-alpha's training speed markedly surpasses existing large-scale T2I models, e.g., PIXART-alpha only takes 10.8% of Stable Diffusion v1.5's training time (675 vs. 6,250 A100 GPU days), saving nearly \300,000 (26,000 vs. \320,000) and reducing 90% CO2 emissions. Moreover, compared with a larger SOTA model, RAPHAEL, our training cost is merely 1%. Extensive experiments demonstrate that PIXART-\alpha excels in image quality, artistry, and semantic control. We hope PIXART-\alpha$ will provide new insights to the AIGC community and startups to accelerate building their own high-quality yet low-cost generative models from scratch.

https://huggingface.co/discussions/paper/651b913f26b2dee1ed1d7f5f