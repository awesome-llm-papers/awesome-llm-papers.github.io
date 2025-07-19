---
layout: publication
title: Training-free Layout Control With Cross-attention Guidance
authors: Chen Minghao, Laina Iro, Vedaldi Andrea
conference: 2024 IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)
year: 2023
bibkey: chen2023training
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.03373'}]
tags: [Training Techniques, Attention Mechanism, Alt, Prompting, Evaluation, Model
    Architecture, Applications, Fine Tuning, Datasets, Merging]
---
Recent diffusion-based generators can produce high-quality images from
textual prompts. However, they often disregard textual instructions that
specify the spatial layout of the composition. We propose a simple approach
that achieves robust layout control without the need for training or
fine-tuning of the image generator. Our technique manipulates the
cross-attention layers that the model uses to interface textual and visual
information and steers the generation in the desired direction given, e.g., a
user-specified layout. To determine how to best guide attention, we study the
role of attention maps and explore two alternative strategies, forward and
backward guidance. We thoroughly evaluate our approach on three benchmarks and
provide several qualitative examples and a comparative analysis of the two
strategies that demonstrate the superiority of backward guidance compared to
forward guidance, as well as prior work. We further demonstrate the versatility
of layout guidance by extending it to applications such as editing the layout
and context of real images.