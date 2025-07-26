---
layout: publication
title: 'An Image Is Worth More Than 16x16 Patches: Exploring Transformers On Individual
  Pixels'
authors: Duy-kien Nguyen, Mahmoud Assran, Unnat Jain, Martin R. Oswald, Cees G. M.
  Snoek, Xinlei Chen
conference: No Venue
year: 2024
bibkey: nguyen2024image
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2406.09415'}]
tags: ["Model Architecture"]
short_authors: Nguyen et al.
---
This work does not introduce a new method. Instead, we present an interesting finding that questions the necessity of the inductive bias -- locality in modern computer vision architectures. Concretely, we find that vanilla Transformers can operate by directly treating each individual pixel as a token and achieve highly performant results. This is substantially different from the popular design in Vision Transformer, which maintains the inductive bias from ConvNets towards local neighborhoods (e.g. by treating each 16x16 patch as a token). We mainly showcase the effectiveness of pixels-as-tokens across three well-studied tasks in computer vision: supervised learning for object classification, self-supervised learning via masked autoencoding, and image generation with diffusion models. Although directly operating on individual pixels is less computationally practical, we believe the community must be aware of this surprising piece of knowledge when devising the next generation of neural architectures for computer vision.

https://huggingface.co/discussions/paper/666ba4cd3814e415474a90b0