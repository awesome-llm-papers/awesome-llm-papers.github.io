---
layout: publication
title: 'Dream3d: Zero-shot Text-to-3d Synthesis Using 3D Shape Prior And Text-to-image
  Diffusion Models'
authors: Xu et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: xu2022dream3d
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.14704'}]
tags: [Training Techniques, Prompting, CVPR, Efficiency And Optimization, Merging]
---
Recent CLIP-guided 3D optimization methods, such as DreamFields and
PureCLIPNeRF, have achieved impressive results in zero-shot text-to-3D
synthesis. However, due to scratch training and random initialization without
prior knowledge, these methods often fail to generate accurate and faithful 3D
structures that conform to the input text. In this paper, we make the first
attempt to introduce explicit 3D shape priors into the CLIP-guided 3D
optimization process. Specifically, we first generate a high-quality 3D shape
from the input text in the text-to-shape stage as a 3D shape prior. We then use
it as the initialization of a neural radiance field and optimize it with the
full prompt. To address the challenging text-to-shape generation task, we
present a simple yet effective approach that directly bridges the text and
image modalities with a powerful text-to-image diffusion model. To narrow the
style domain gap between the images synthesized by the text-to-image diffusion
model and shape renderings used to train the image-to-shape generator, we
further propose to jointly optimize a learnable text prompt and fine-tune the
text-to-image diffusion model for rendering-style image generation. Our method,
Dream3D, is capable of generating imaginative 3D content with superior visual
quality and shape accuracy compared to state-of-the-art methods.