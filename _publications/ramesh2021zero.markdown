---
layout: publication
title: Zero-shot Text-to-image Generation
authors: Aditya Ramesh, Mikhail Pavlov, Gabriel Goh, Scott Gray, Chelsea Voss, Alec
  Radford, Mark Chen, Ilya Sutskever
conference: Arxiv
year: 2021
bibkey: ramesh2021zero
citations: 1075
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.12092'}]
tags: ["Datasets", "Model Architecture", "Training Techniques"]
short_authors: Ramesh et al.
---
Text-to-image generation has traditionally focused on finding better modeling
assumptions for training on a fixed dataset. These assumptions might involve
complex architectures, auxiliary losses, or side information such as object
part labels or segmentation masks supplied during training. We describe a
simple approach for this task based on a transformer that autoregressively
models the text and image tokens as a single stream of data. With sufficient
data and scale, our approach is competitive with previous domain-specific
models when evaluated in a zero-shot fashion.