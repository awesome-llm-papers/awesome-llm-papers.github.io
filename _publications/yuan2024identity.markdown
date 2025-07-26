---
layout: publication
title: Identity-preserving Text-to-video Generation By Frequency Decomposition
authors: Shenghai Yuan, Jinfa Huang, Xianyi He, Yunyuan Ge, Yujun Shi, Liuhan Chen,
  Jiebo Luo, Li Yuan
conference: No Venue
year: 2024
bibkey: yuan2024identity
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/674698d69c25e8cefac02743'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2411.17440'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Yuan et al.
---
Identity-preserving text-to-video (IPT2V) generation aims to create high-fidelity videos with consistent human identity. It is an important task in video generation but remains an open problem for generative models. This paper pushes the technical frontier of IPT2V in two directions that have not been resolved in literature: (1) A tuning-free pipeline without tedious case-by-case finetuning, and (2) A frequency-aware heuristic identity-preserving DiT-based control scheme. We propose ConsisID, a tuning-free DiT-based controllable IPT2V model to keep human identity consistent in the generated video. Inspired by prior findings in frequency analysis of diffusion transformers, it employs identity-control signals in the frequency domain, where facial features can be decomposed into low-frequency global features and high-frequency intrinsic features. First, from a low-frequency perspective, we introduce a global facial extractor, which encodes reference images and facial key points into a latent space, generating features enriched with low-frequency information. These features are then integrated into shallow layers of the network to alleviate training challenges associated with DiT. Second, from a high-frequency perspective, we design a local facial extractor to capture high-frequency details and inject them into transformer blocks, enhancing the model's ability to preserve fine-grained features. We propose a hierarchical training strategy to leverage frequency information for identity preservation, transforming a vanilla pre-trained video generation model into an IPT2V model. Extensive experiments demonstrate that our frequency-aware heuristic scheme provides an optimal control solution for DiT-based models. Thanks to this scheme, our ConsisID generates high-quality, identity-preserving videos, making strides towards more effective IPT2V.

https://huggingface.co/discussions/paper/674698d69c25e8cefac02743