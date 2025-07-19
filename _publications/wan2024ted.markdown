---
layout: publication
title: 'TED-VITON: Transformer-empowered Diffusion Models For Virtual Try-on'
authors: Wan et al.
conference: 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition
year: 2024
bibkey: wan2024ted
citations: 412
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.17017'}]
tags: [RAG, Prompting, Tools, Evaluation, CVPR, Transformer, Model Architecture, Language
    Modeling, Reinforcement Learning, Datasets, Merging]
---
Recent advancements in Virtual Try-On (VTO) have demonstrated exceptional
efficacy in generating realistic images and preserving garment details, largely
attributed to the robust generative capabilities of text-to-image (T2I)
diffusion backbones. However, the T2I models that underpin these methods have
become outdated, thereby limiting the potential for further improvement in VTO.
Additionally, current methods face notable challenges in accurately rendering
text on garments without distortion and preserving fine-grained details, such
as textures and material fidelity. The emergence of Diffusion Transformer (DiT)
based T2I models has showcased impressive performance and offers a promising
opportunity for advancing VTO. Directly applying existing VTO techniques to
transformer-based T2I models is ineffective due to substantial architectural
differences, which hinder their ability to fully leverage the models' advanced
capabilities for improved text generation. To address these challenges and
unlock the full potential of DiT-based T2I models for VTO, we propose
TED-VITON, a novel framework that integrates a Garment Semantic (GS) Adapter
for enhancing garment-specific features, a Text Preservation Loss to ensure
accurate and distortion-free text rendering, and a constraint mechanism to
generate prompts by optimizing Large Language Model (LLM). These innovations
enable state-of-the-art (SOTA) performance in visual quality and text fidelity,
establishing a new benchmark for VTO task. Project page:
https://zhenchenwan.github.io/TED-VITON/