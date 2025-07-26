---
layout: publication
title: 'Bitsfusion: 1.99 Bits Weight Quantization Of Diffusion Model'
authors: Yang Sui, Yanyu Li, Anil Kag, Yerlan Idelbayev, Junli Cao, Ju Hu, Dhritiman
  Sagar, Bo Yuan, Sergey Tulyakov, Jian Ren
conference: No Venue
year: 2024
bibkey: sui2024bitsfusion
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2406.04333'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Sui et al.
---
Diffusion-based image generation models have achieved great success in recent years by showing the capability of synthesizing high-quality content. However, these models contain a huge number of parameters, resulting in a significantly large model size. Saving and transferring them is a major bottleneck for various applications, especially those running on resource-constrained devices. In this work, we develop a novel weight quantization method that quantizes the UNet from Stable Diffusion v1.5 to 1.99 bits, achieving a model with 7.9X smaller size while exhibiting even better generation quality than the original one. Our approach includes several novel techniques, such as assigning optimal bits to each layer, initializing the quantized model for better performance, and improving the training strategy to dramatically reduce quantization error. Furthermore, we extensively evaluate our quantized model across various benchmark datasets and through human evaluation to demonstrate its superior generation quality.

https://huggingface.co/discussions/paper/6662731c3388180cc4f98392