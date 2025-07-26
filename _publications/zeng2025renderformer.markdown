---
layout: publication
title: 'Renderformer: Transformer-based Neural Rendering Of Triangle Meshes With Global
  Illumination'
authors: Chong Zeng, Yue Dong, Pieter Peers, Hongzhi Wu, Xin Tong
conference: No Venue
year: 2025
bibkey: zeng2025renderformer
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.21925'}]
tags: ["Model Architecture"]
short_authors: Zeng et al.
---
We present RenderFormer, a neural rendering pipeline that directly renders an image from a triangle-based representation of a scene with full global illumination effects and that does not require per-scene training or fine-tuning. Instead of taking a physics-centric approach to rendering, we formulate rendering as a sequence-to-sequence transformation where a sequence of tokens representing triangles with reflectance properties is converted to a sequence of output tokens representing small patches of pixels. RenderFormer follows a two stage pipeline: a view-independent stage that models triangle-to-triangle light transport, and a view-dependent stage that transforms a token representing a bundle of rays to the corresponding pixel values guided by the triangle-sequence from the view-independent stage. Both stages are based on the transformer architecture and are learned with minimal prior constraints. We demonstrate and evaluate RenderFormer on scenes with varying complexity in shape and light transport.

https://huggingface.co/discussions/paper/6837c23ccce400abe6f18812