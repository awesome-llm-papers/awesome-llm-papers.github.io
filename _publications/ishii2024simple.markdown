---
layout: publication
title: 'A Simple But Strong Baseline For Sounding Video Generation: Effective Adaptation
  Of Audio And Video Diffusion Models For Joint Generation'
authors: Ishii et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: ishii2024simple
citations: 64
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2409.17550'}]
tags: [Attention Mechanism, CVPR, Ethics And Bias, Transformer, Model Architecture,
  Multimodal Models, Merging]
---
In this work, we build a simple but strong baseline for sounding video
generation. Given base diffusion models for audio and video, we integrate them
with additional modules into a single model and train it to make the model
jointly generate audio and video. To enhance alignment between audio-video
pairs, we introduce two novel mechanisms in our model. The first one is
timestep adjustment, which provides different timestep information to each base
model. It is designed to align how samples are generated along with timesteps
across modalities. The second one is a new design of the additional modules,
termed Cross-Modal Conditioning as Positional Encoding (CMC-PE). In CMC-PE,
cross-modal information is embedded as if it represents temporal position
information, and the embeddings are fed into the model like positional
encoding. Compared with the popular cross-attention mechanism, CMC-PE provides
a better inductive bias for temporal alignment in the generated data.
Experimental results validate the effectiveness of the two newly introduced
mechanisms and also demonstrate that our method outperforms existing methods.