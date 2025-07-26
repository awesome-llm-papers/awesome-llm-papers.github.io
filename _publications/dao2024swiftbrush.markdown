---
layout: publication
title: 'Swiftbrush V2: Make Your One-step Diffusion Model Better Than Its Teacher'
authors: Trung Dao, Thuan Hoang Nguyen, Thanh Le, Duc Vu, Khoi Nguyen, Cuong Pham,
  Anh Tran
conference: No Venue
year: 2024
bibkey: dao2024swiftbrush
additional_links: [{name: Code, url: 'https://github.com/vinairesearch/swiftbrushv2'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/66cd4c03332ce5c746878f0f'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2408.14176'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Dao et al.
---
In this paper, we aim to enhance the performance of SwiftBrush, a prominent one-step text-to-image diffusion model, to be competitive with its multi-step Stable Diffusion counterpart. Initially, we explore the quality-diversity trade-off between SwiftBrush and SD Turbo: the former excels in image diversity, while the latter excels in image quality. This observation motivates our proposed modifications in the training methodology, including better weight initialization and efficient LoRA training. Moreover, our introduction of a novel clamped CLIP loss enhances image-text alignment and results in improved image quality. Remarkably, by combining the weights of models trained with efficient LoRA and full training, we achieve a new state-of-the-art one-step diffusion model, achieving an FID of 8.14 and surpassing all GAN-based and multi-step Stable Diffusion models. The evaluation code is available at: https://github.com/vinairesearch/swiftbrushv2.

https://huggingface.co/discussions/paper/66cd4c03332ce5c746878f0f