---
layout: publication
title: 'Faceformer: Speech-driven 3D Facial Animation With Transformers'
authors: Yingruo Fan, Zhaojiang Lin, Jun Saito, Wenping Wang, Taku Komura
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: fan2021faceformer
citations: 118
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.05329'}]
tags: ["CVPR", "Model Architecture"]
short_authors: Fan et al.
---
Speech-driven 3D facial animation is challenging due to the complex geometry
of human faces and the limited availability of 3D audio-visual data. Prior
works typically focus on learning phoneme-level features of short audio windows
with limited context, occasionally resulting in inaccurate lip movements. To
tackle this limitation, we propose a Transformer-based autoregressive model,
FaceFormer, which encodes the long-term audio context and autoregressively
predicts a sequence of animated 3D face meshes. To cope with the data scarcity
issue, we integrate the self-supervised pre-trained speech representations.
Also, we devise two biased attention mechanisms well suited to this specific
task, including the biased cross-modal multi-head (MH) attention and the biased
causal MH self-attention with a periodic positional encoding strategy. The
former effectively aligns the audio-motion modalities, whereas the latter
offers abilities to generalize to longer audio sequences. Extensive experiments
and a perceptual user study show that our approach outperforms the existing
state-of-the-arts. The code will be made available.