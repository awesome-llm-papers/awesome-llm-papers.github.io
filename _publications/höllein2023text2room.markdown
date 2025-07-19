---
layout: publication
title: 'Text2room: Extracting Textured 3D Meshes From 2D Text-to-image Models'
authors: "H\xF6llein et al."
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2023
bibkey: "h\xF6llein2023text2room"
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.11989'}]
tags: [Prompting, RAG, ICCV, Evaluation]
---
We present Text2Room, a method for generating room-scale textured 3D meshes
from a given text prompt as input. To this end, we leverage pre-trained 2D
text-to-image models to synthesize a sequence of images from different poses.
In order to lift these outputs into a consistent 3D scene representation, we
combine monocular depth estimation with a text-conditioned inpainting model.
The core idea of our approach is a tailored viewpoint selection such that the
content of each image can be fused into a seamless, textured 3D mesh. More
specifically, we propose a continuous alignment strategy that iteratively fuses
scene frames with the existing geometry to create a seamless mesh. Unlike
existing works that focus on generating single objects or zoom-out trajectories
from text, our method generates complete 3D scenes with multiple objects and
explicit 3D geometry. We evaluate our approach using qualitative and
quantitative metrics, demonstrating it as the first method to generate
room-scale 3D geometry with compelling textures from only text as input.