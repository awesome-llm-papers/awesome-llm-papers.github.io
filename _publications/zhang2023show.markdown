---
layout: publication
title: 'Show-1: Marrying Pixel And Latent Diffusion Models For Text-to-video Generation'
authors: David Junhao Zhang et al.
conference: Arxiv
year: 2023
citations: 23
bibkey: zhang2023show
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2309.15818'}, {name: Code,
    url: 'https://github.com/showlab/Show-1'}]
tags: [Merging, Attention Mechanism, Has Code, Applications, Model Architecture]
---
Significant advancements have been achieved in the realm of large-scale pre-trained text-to-video Diffusion Models (VDMs). However, previous methods either rely solely on pixel-based VDMs, which come with high computational costs, or on latent-based VDMs, which often struggle with precise text-video alignment. In this paper, we are the first to propose a hybrid model, dubbed as Show-1, which marries pixel-based and latent-based VDMs for text-to-video generation. Our model first uses pixel-based VDMs to produce a low-resolution video of strong text-video correlation. After that, we propose a novel expert translation method that employs the latent-based VDMs to further upsample the low-resolution video to high resolution, which can also remove potential artifacts and corruptions from low-resolution videos. Compared to latent VDMs, Show-1 can produce high-quality videos of precise text-video alignment; Compared to pixel VDMs, Show-1 is much more efficient (GPU memory usage during inference is 15G vs 72G). Furthermore, our Show-1 model can be readily adapted for motion customization and video stylization applications through simple temporal attention layer finetuning. Our model achieves state-of-the-art performance on standard video generation benchmarks. Our code and model weights are publicly available at https://github.com/showlab/Show-1.