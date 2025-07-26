---
layout: publication
title: 'Autoregressive Model Beats Diffusion: Llama For Scalable Image Generation'
authors: Peize Sun, Yi Jiang, Shoufa Chen, Shilong Zhang, Bingyue Peng, Ping Luo,
  Zehuan Yuan
conference: No Venue
year: 2024
bibkey: sun2024autoregressive
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6667c71ee490a870be48db9e'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2406.06525'}]
tags: ["Evaluation", "Training Techniques"]
short_authors: Sun et al.
---
We introduce LlamaGen, a new family of image generation models that apply original ``next-token prediction'' paradigm of large language models to visual generation domain. It is an affirmative answer to whether vanilla autoregressive models, e.g., Llama, without inductive biases on visual signals can achieve state-of-the-art image generation performance if scaling properly. We reexamine design spaces of image tokenizers, scalability properties of image generation models, and their training data quality. The outcome of this exploration consists of: (1) An image tokenizer with downsample ratio of 16, reconstruction quality of 0.94 rFID and codebook usage of 97% on ImageNet benchmark. (2) A series of class-conditional image generation models ranging from 111M to 3.1B parameters, achieving 2.18 FID on ImageNet 256x256 benchmarks, outperforming the popular diffusion models such as LDM, DiT. (3) A text-conditional image generation model with 775M parameters, from two-stage training on LAION-COCO and high aesthetics quality images, demonstrating competitive performance of visual quality and text alignment. (4) We verify the effectiveness of LLM serving frameworks in optimizing the inference speed of image generation models and achieve 326% - 414% speedup. We release all models and codes to facilitate open-source community of visual generation and multimodal foundation models.

https://huggingface.co/discussions/paper/6667c71ee490a870be48db9e