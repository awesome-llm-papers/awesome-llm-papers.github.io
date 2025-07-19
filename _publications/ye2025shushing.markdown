---
layout: publication
title: Shushing! Let's Imagine An Authentic Speech From The Silent Video
authors: Ye Jiaxin, Shan Hongming
conference: 2017 IEEE International Conference on Computer Vision Workshops (ICCVW)
year: 2025
bibkey: ye2025shushing
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.14928'}]
tags: [ICCV, Prompting, Masked Language Model, Tools, Transformer, BERT, Model Architecture,
  Language Modeling, Applications, Multimodal Models, Merging]
---
Vision-guided speech generation aims to produce authentic speech from facial
appearance or lip motions without relying on auditory signals, offering
significant potential for applications such as dubbing in filmmaking and
assisting individuals with aphonia. Despite recent progress, existing methods
struggle to achieve unified cross-modal alignment across semantics, timbre, and
emotional prosody from visual cues, prompting us to propose Consistent
Video-to-Speech (CV2S) as an extended task to enhance cross-modal consistency.
To tackle emerging challenges, we introduce ImaginTalk, a novel cross-modal
diffusion framework that generates faithful speech using only visual input,
operating within a discrete space. Specifically, we propose a discrete lip
aligner that predicts discrete speech tokens from lip videos to capture
semantic information, while an error detector identifies misaligned tokens,
which are subsequently refined through masked language modeling with BERT. To
further enhance the expressiveness of the generated speech, we develop a style
diffusion transformer equipped with a face-style adapter that adaptively
customizes identity and prosody dynamics across both the channel and temporal
dimensions while ensuring synchronization with lip-aware semantic features.
Extensive experiments demonstrate that ImaginTalk can generate high-fidelity
speech with more accurate semantic details and greater expressiveness in timbre
and emotion compared to state-of-the-art baselines. Demos are shown at our
project page: https://imagintalk.github.io.