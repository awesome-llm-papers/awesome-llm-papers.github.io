---
layout: publication
title: 'Rerender A Video: Zero-shot Text-guided Video-to-video Translation'
authors: Shuai Yang, Yifan Zhou, Ziwei Liu, Chen Change Loy
conference: No Venue
year: 2023
bibkey: yang2023rerender
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2306.07954'}]
tags: ["Tools"]
short_authors: Yang et al.
---
Large text-to-image diffusion models have exhibited impressive proficiency in generating high-quality images. However, when applying these models to video domain, ensuring temporal consistency across video frames remains a formidable challenge. This paper proposes a novel zero-shot text-guided video-to-video translation framework to adapt image models to videos. The framework includes two parts: key frame translation and full video translation. The first part uses an adapted diffusion model to generate key frames, with hierarchical cross-frame constraints applied to enforce coherence in shapes, textures and colors. The second part propagates the key frames to other frames with temporal-aware patch matching and frame blending. Our framework achieves global style and local texture temporal consistency at a low cost (without re-training or optimization). The adaptation is compatible with existing image diffusion techniques, allowing our framework to take advantage of them, such as customizing a specific subject with LoRA, and introducing extra spatial guidance with ControlNet. Extensive experimental results demonstrate the effectiveness of our proposed framework over existing methods in rendering high-quality and temporally-coherent videos.

https://huggingface.co/discussions/paper/6489263250aa32474db5827e