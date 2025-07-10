---
layout: publication
title: 'Pandagpt: One Model To Instruction-follow Them All'
authors: Yixuan Su et al.
conference: Arxiv
year: 2023
citations: 44
bibkey: su2023one
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.16355'}, {name: Code,
    url: 'https://panda-gpt.github.io/'}]
tags: [Has Code, Model Architecture, GPT, Multimodal Models, Training Techniques]
---
We present PandaGPT, an approach to emPower large lANguage moDels with visual
and Auditory instruction-following capabilities. Our pilot experiments show
that PandaGPT can perform complex tasks such as detailed image description
generation, writing stories inspired by videos, and answering questions about
audios. More interestingly, PandaGPT can take multimodal inputs simultaneously
and compose their semantics naturally. For example, PandaGPT can connect how
objects look in an image/video and how they sound in an audio. To do so,
PandaGPT combines the multimodal encoders from ImageBind and the large language
models from Vicuna. Notably, only aligned image-text pairs are required for the
training of PandaGPT. Thanks to the strong capability of ImageBind in embedding
data from different modalities into the same space, PandaGPT displays emergent,
i.e. zero-shot, cross-modal behaviors for data other than image and text (e.g.,
video, audio, depth, thermal, and IMU). We hope that PandaGPT serves as an
initial step toward building AGI that can perceive and understand inputs in
different modalities holistically, as we humans do. Our project page is at
https://panda-gpt.github.io/.