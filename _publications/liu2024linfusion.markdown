---
layout: publication
title: 'Linfusion: 1 GPU, 1 Minute, 16K Image'
authors: Songhua Liu, Weihao Yu, Zhenxiong Tan, Xinchao Wang
conference: No Venue
year: 2024
bibkey: liu2024linfusion
additional_links: [{name: Code, url: 'https://github.com/Huage001/LinFusion'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/66d7ca360d88366001a8659d'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2409.02097'}]
tags: ["Has Code"]
short_authors: Liu et al.
---
Modern diffusion models, particularly those utilizing a Transformer-based UNet for denoising, rely heavily on self-attention operations to manage complex spatial relationships, thus achieving impressive generation performance. However, this existing paradigm faces significant challenges in generating high-resolution visual content due to its quadratic time and memory complexity with respect to the number of spatial tokens. To address this limitation, we aim at a novel linear attention mechanism as an alternative in this paper. Specifically, we begin our exploration from recently introduced models with linear complexity, e.g., Mamba, Mamba2, and Gated Linear Attention, and identify two key features-attention normalization and non-causal inference-that enhance high-resolution visual generation performance. Building on these insights, we introduce a generalized linear attention paradigm, which serves as a low-rank approximation of a wide spectrum of popular linear token mixers. To save the training cost and better leverage pre-trained models, we initialize our models and distill the knowledge from pre-trained StableDiffusion (SD). We find that the distilled model, termed LinFusion, achieves performance on par with or superior to the original SD after only modest training, while significantly reducing time and memory complexity. Extensive experiments on SD-v1.5, SD-v2.1, and SD-XL demonstrate that LinFusion delivers satisfactory zero-shot cross-resolution generation performance, generating high-resolution images like 16K resolution. Moreover, it is highly compatible with pre-trained SD components, such as ControlNet and IP-Adapter, requiring no adaptation efforts. Codes are available at https://github.com/Huage001/LinFusion.

https://huggingface.co/discussions/paper/66d7ca360d88366001a8659d