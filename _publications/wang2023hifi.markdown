---
layout: publication
title: 'Hifi Tuner: High-fidelity Subject-driven Fine-tuning For Diffusion Models'
authors: Wang et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: wang2023hifi
citations: 1132
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.00079'}]
tags: [RAG, Training Techniques, Tools, CVPR, Evaluation, Fine Tuning, Datasets, Merging]
---
This paper explores advancements in high-fidelity personalized image
generation through the utilization of pre-trained text-to-image diffusion
models. While previous approaches have made significant strides in generating
versatile scenes based on text descriptions and a few input images, challenges
persist in maintaining the subject fidelity within the generated images. In
this work, we introduce an innovative algorithm named HiFi Tuner to enhance the
appearance preservation of objects during personalized image generation. Our
proposed method employs a parameter-efficient fine-tuning framework, comprising
a denoising process and a pivotal inversion process. Key enhancements include
the utilization of mask guidance, a novel parameter regularization technique,
and the incorporation of step-wise subject representations to elevate the
sample fidelity. Additionally, we propose a reference-guided generation
approach that leverages the pivotal inversion of a reference image to mitigate
unwanted subject variations and artifacts. We further extend our method to a
novel image editing task: substituting the subject in an image through textual
manipulations. Experimental evaluations conducted on the DreamBooth dataset
using the Stable Diffusion model showcase promising results. Fine-tuning solely
on textual embeddings improves CLIP-T score by 3.6 points and improves DINO
score by 9.6 points over Textual Inversion. When fine-tuning all parameters,
HiFi Tuner improves CLIP-T score by 1.2 points and improves DINO score by 1.2
points over DreamBooth, establishing a new state of the art.