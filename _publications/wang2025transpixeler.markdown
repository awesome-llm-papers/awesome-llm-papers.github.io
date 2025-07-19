---
layout: publication
title: 'Transpixeler: Advancing Text-to-video Generation With Transparency'
authors: Wang et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2025
bibkey: wang2025transpixeler
citations: 125
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.03006'}]
tags: [RAG, Training Techniques, Attention Mechanism, Ethics And Bias, Transformer,
  Model Architecture, Applications, Fine Tuning, AAAI, Datasets, Merging]
---
Text-to-video generative models have made significant strides, enabling
diverse applications in entertainment, advertising, and education. However,
generating RGBA video, which includes alpha channels for transparency, remains
a challenge due to limited datasets and the difficulty of adapting existing
models. Alpha channels are crucial for visual effects (VFX), allowing
transparent elements like smoke and reflections to blend seamlessly into
scenes. We introduce TransPixeler, a method to extend pretrained video models
for RGBA generation while retaining the original RGB capabilities. TransPixar
leverages a diffusion transformer (DiT) architecture, incorporating
alpha-specific tokens and using LoRA-based fine-tuning to jointly generate RGB
and alpha channels with high consistency. By optimizing attention mechanisms,
TransPixar preserves the strengths of the original RGB model and achieves
strong alignment between RGB and alpha channels despite limited training data.
Our approach effectively generates diverse and consistent RGBA videos,
advancing the possibilities for VFX and interactive content creation.