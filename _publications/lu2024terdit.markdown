---
layout: publication
title: 'Terdit: Ternary Diffusion Models With Transformers'
authors: Lu et al.
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2024
bibkey: lu2024terdit
citations: 445
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.14854'}]
tags: [ICCV, Training Techniques, Alt, Transformer, Model Architecture, Efficiency
    And Optimization, Reinforcement Learning, Fine Tuning, Quantization, Merging]
---
Recent developments in large-scale pre-trained text-to-image diffusion models
have significantly improved the generation of high-fidelity images,
particularly with the emergence of diffusion transformer models (DiTs). Among
diffusion models, diffusion transformers have demonstrated superior
image-generation capabilities, boosting lower FID scores and higher
scalability. However, deploying large-scale DiT models can be expensive due to
their excessive parameter numbers. Although existing research has explored
efficient deployment techniques for diffusion models, such as model
quantization, there is still little work concerning DiT-based models. To tackle
this research gap, we propose TerDiT, the first quantization-aware training
(QAT) and efficient deployment scheme for extremely low-bit diffusion
transformer models. We focus on the ternarization of DiT networks, with model
sizes ranging from 600M to 4.2B, and image resolution from 256\\(\times\\)256 to
512\\(\times\\)512. Our work contributes to the exploration of efficient deployment
of large-scale DiT models, demonstrating the feasibility of training extremely
low-bit DiT models from scratch while maintaining competitive image generation
capacities compared to full-precision models. Our code and pre-trained TerDiT
checkpoints have been released at https://github.com/Lucky-Lance/TerDiT.