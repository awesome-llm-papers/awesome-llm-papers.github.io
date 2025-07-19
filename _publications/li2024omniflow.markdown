---
layout: publication
title: 'Omniflow: Any-to-any Generation With Multi-modal Rectified Flows'
authors: Li et al.
conference: Linguistics and Philosophy
year: 2024
bibkey: li2024omniflow
citations: 82
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.01169'}]
tags: [Training Techniques, Tools, Transformer, Model Architecture, Language Modeling,
  Fine Tuning, Merging]
---
We introduce OmniFlow, a novel generative model designed for any-to-any
generation tasks such as text-to-image, text-to-audio, and audio-to-image
synthesis. OmniFlow advances the rectified flow (RF) framework used in
text-to-image models to handle the joint distribution of multiple modalities.
It outperforms previous any-to-any models on a wide range of tasks, such as
text-to-image and text-to-audio synthesis. Our work offers three key
contributions: First, we extend RF to a multi-modal setting and introduce a
novel guidance mechanism, enabling users to flexibly control the alignment
between different modalities in the generated outputs. Second, we propose a
novel architecture that extends the text-to-image MMDiT architecture of Stable
Diffusion 3 and enables audio and text generation. The extended modules can be
efficiently pretrained individually and merged with the vanilla text-to-image
MMDiT for fine-tuning. Lastly, we conduct a comprehensive study on the design
choices of rectified flow transformers for large-scale audio and text
generation, providing valuable insights into optimizing performance across
diverse modalities. The Code will be available at
https://github.com/jacklishufan/OmniFlows.