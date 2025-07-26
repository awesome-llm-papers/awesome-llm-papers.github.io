---
layout: publication
title: 'LHM: Large Animatable Human Reconstruction Model From A Single Image In Seconds'
authors: Lingteng Qiu, Xiaodong Gu, Peihao Li, Qi Zuo, Weichao Shen, Junfei Zhang,
  Kejie Qiu, Weihao Yuan, Guanying Chen, Zilong Dong, Liefeng Bo
conference: No Venue
year: 2025
bibkey: qiu2025lhm
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67dacb499c49701f604e4454'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2503.10625'}]
tags: ["Efficiency", "Model Architecture", "Training Techniques"]
short_authors: Qiu et al.
---
Animatable 3D human reconstruction from a single image is a challenging problem due to the ambiguity in decoupling geometry, appearance, and deformation. Recent advances in 3D human reconstruction mainly focus on static human modeling, and the reliance of using synthetic 3D scans for training limits their generalization ability. Conversely, optimization-based video methods achieve higher fidelity but demand controlled capture conditions and computationally intensive refinement processes. Motivated by the emergence of large reconstruction models for efficient static reconstruction, we propose LHM (Large Animatable Human Reconstruction Model) to infer high-fidelity avatars represented as 3D Gaussian splatting in a feed-forward pass. Our model leverages a multimodal transformer architecture to effectively encode the human body positional features and image features with attention mechanism, enabling detailed preservation of clothing geometry and texture. To further boost the face identity preservation and fine detail recovery, we propose a head feature pyramid encoding scheme to aggregate multi-scale features of the head regions. Extensive experiments demonstrate that our LHM generates plausible animatable human in seconds without post-processing for face and hands, outperforming existing methods in both reconstruction accuracy and generalization ability.

https://huggingface.co/discussions/paper/67dacb499c49701f604e4454