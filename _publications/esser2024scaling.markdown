---
layout: publication
title: Scaling Rectified Flow Transformers For High-resolution Image Synthesis
authors: Esser et al.
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: esser2024scaling
citations: 1370
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.03206'}]
tags: [Training Techniques, CVPR, Evaluation, Ethics And Bias, Transformer, Model
    Architecture, Merging]
---
Diffusion models create data from noise by inverting the forward paths of
data towards noise and have emerged as a powerful generative modeling technique
for high-dimensional, perceptual data such as images and videos. Rectified flow
is a recent generative model formulation that connects data and noise in a
straight line. Despite its better theoretical properties and conceptual
simplicity, it is not yet decisively established as standard practice. In this
work, we improve existing noise sampling techniques for training rectified flow
models by biasing them towards perceptually relevant scales. Through a
large-scale study, we demonstrate the superior performance of this approach
compared to established diffusion formulations for high-resolution
text-to-image synthesis. Additionally, we present a novel transformer-based
architecture for text-to-image generation that uses separate weights for the
two modalities and enables a bidirectional flow of information between image
and text tokens, improving text comprehension, typography, and human preference
ratings. We demonstrate that this architecture follows predictable scaling
trends and correlates lower validation loss to improved text-to-image synthesis
as measured by various metrics and human evaluations. Our largest models
outperform state-of-the-art models, and we will make our experimental data,
code, and model weights publicly available.