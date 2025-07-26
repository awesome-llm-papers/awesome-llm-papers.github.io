---
layout: publication
title: 'Sharegpt-4o-image: Aligning Multimodal Models With Gpt-4o-level Image Generation'
authors: Junying Chen, Zhenyang Cai, Pengcheng Chen, Shunian Chen, Ke Ji, Xidong Wang,
  Yunjin Yang, Benyou Wang
conference: No Venue
year: 2025
bibkey: chen2025sharegpt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.18095'}]
tags: ["Datasets", "Model Architecture", "Training Techniques"]
short_authors: Chen et al.
---
Recent advances in multimodal generative models have unlocked photorealistic, instruction-aligned image generation, yet leading systems like GPT-4o-Image remain proprietary and inaccessible. To democratize these capabilities, we present ShareGPT-4o-Image, the first dataset comprising 45K text-to-image and 46K text-and-image-to-image data, all synthesized using GPT-4o's image generation capabilities for distilling its advanced image generation abilities. Leveraging this dataset, we develop Janus-4o, a multimodal large language model capable of both text-to-image and text-and-image-to-image generation. Janus-4o not only significantly improves text-to-image generation over its predecessor, Janus-Pro, but also newly supports text-and-image-to-image generation. Notably, it achieves impressive performance in text-and-image-to-image generation from scratch, using only 91K synthetic samples and 6 hours of training on an 8 A800-GPU machine. We hope the release of ShareGPT-4o-Image and Janus-4o will foster open research in photorealistic, instruction-aligned image generation.

https://huggingface.co/discussions/paper/685a0ac30e4ad7e2197584f2