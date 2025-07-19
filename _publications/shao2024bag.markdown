---
layout: publication
title: Bag Of Design Choices For Inference Of High-resolution Masked Generative Transformer
authors: Shao et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: shao2024bag
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.10781'}]
tags: [GPT, CVPR, Transformer, Model Architecture, Efficiency And Optimization, Language
    Modeling, Reinforcement Learning, Fine Tuning, Merging]
---
Text-to-image diffusion models (DMs) develop at an unprecedented pace,
supported by thorough theoretical exploration and empirical analysis.
Unfortunately, the discrepancy between DMs and autoregressive models (ARMs)
complicates the path toward achieving the goal of unified vision and language
generation. Recently, the masked generative Transformer (MGT) serves as a
promising intermediary between DM and ARM by predicting randomly masked image
tokens (i.e., masked image modeling), combining the efficiency of DM with the
discrete token nature of ARM. However, we find that the comprehensive analyses
regarding the inference for MGT are virtually non-existent, and thus we aim to
present positive design choices to fill this gap. We propose and redesign a set
of enhanced inference techniques tailored for MGT, providing a detailed
analysis of their performance. Additionally, we explore several DM-based
approaches aimed at accelerating the sampling process on MGT. Extensive
experiments and empirical analyses on the recent SOTA MGT, such as MaskGIT and
Meissonic lead to concrete and effective design choices, and these design
choices can be merged to achieve further performance gains. For instance, in
terms of enhanced inference, we achieve winning rates of approximately 70%
compared to vanilla sampling on HPS v2 with Meissonic-1024x1024.