---
layout: publication
title: Detailed Human-centric Text Description-driven Large Scene Synthesis
authors: Kim et al.
conference: 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition
year: 2023
bibkey: kim2023detailed
citations: 98
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.18654'}]
tags: [RAG, CVPR, Merging]
---
Text-driven large scene image synthesis has made significant progress with
diffusion models, but controlling it is challenging. While using additional
spatial controls with corresponding texts has improved the controllability of
large scene synthesis, it is still challenging to faithfully reflect detailed
text descriptions without user-provided controls. Here, we propose
DetText2Scene, a novel text-driven large-scale image synthesis with high
faithfulness, controllability, and naturalness in a global context for the
detailed human-centric text description. Our DetText2Scene consists of 1)
hierarchical keypoint-box layout generation from the detailed description by
leveraging large language model (LLM), 2) view-wise conditioned joint diffusion
process to synthesize a large scene from the given detailed text with
LLM-generated grounded keypoint-box layout and 3) pixel perturbation-based
pyramidal interpolation to progressively refine the large scene for global
coherence. Our DetText2Scene significantly outperforms prior arts in
text-to-large scene synthesis qualitatively and quantitatively, demonstrating
strong faithfulness with detailed descriptions, superior controllability, and
excellent naturalness in a global context.