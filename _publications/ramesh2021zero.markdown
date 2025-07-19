---
layout: publication
title: Zero-shot Text-to-image Generation
authors: Ramesh et al.
conference: Arxiv
year: 2021
bibkey: ramesh2021zero
citations: 1075
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.12092'}]
tags: [Training Techniques, GPT, Transformer, Model Architecture, Datasets]
---
Text-to-image generation has traditionally focused on finding better modeling
assumptions for training on a fixed dataset. These assumptions might involve
complex architectures, auxiliary losses, or side information such as object
part labels or segmentation masks supplied during training. We describe a
simple approach for this task based on a transformer that autoregressively
models the text and image tokens as a single stream of data. With sufficient
data and scale, our approach is competitive with previous domain-specific
models when evaluated in a zero-shot fashion.