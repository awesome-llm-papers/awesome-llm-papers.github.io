---
layout: publication
title: Blending Concepts With Text-to-image Diffusion Models
authors: Olearo et al.
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2025
bibkey: olearo2025blending
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.23630'}]
tags: [ICCV, Training Techniques, Prompting, Tools, Fine Tuning, Merging]
---
Diffusion models have dramatically advanced text-to-image generation in recent years, translating abstract concepts into high-fidelity images with remarkable ease. In this work, we examine whether they can also blend distinct concepts, ranging from concrete objects to intangible ideas, into coherent new visual entities under a zero-shot framework. Specifically, concept blending merges the key attributes of multiple concepts (expressed as textual prompts) into a single, novel image that captures the essence of each concept. We investigate four blending methods, each exploiting different aspects of the diffusion pipeline (e.g., prompt scheduling, embedding interpolation, or layer-wise conditioning). Through systematic experimentation across diverse concept categories, such as merging concrete concepts, synthesizing compound words, transferring artistic styles, and blending architectural landmarks, we show that modern diffusion models indeed exhibit creative blending capabilities without further training or fine-tuning. Our extensive user study, involving 100 participants, reveals that no single approach dominates in all scenarios: each blending technique excels under certain conditions, with factors like prompt ordering, conceptual distance, and random seed affecting the outcome. These findings highlight the remarkable compositional potential of diffusion models while exposing their sensitivity to seemingly minor input variations.