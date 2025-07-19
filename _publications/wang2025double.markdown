---
layout: publication
title: 'Double Visual Defense: Adversarial Pre-training And Instruction Tuning For
  Improving Vision-language Model Robustness'
authors: Wang et al.
conference: 2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: wang2025double
citations: 96
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.09446'}]
tags: [Training Techniques, CVPR, Reinforcement Learning, Security, Fine Tuning, Multimodal
    Models]
---
This paper investigates the robustness of vision-language models against
adversarial visual perturbations and introduces a novel ``double visual
defense" to enhance this robustness. Unlike previous approaches that resort to
lightweight adversarial fine-tuning of a pre-trained CLIP model, we perform
large-scale adversarial vision-language pre-training from scratch using
web-scale data. We then strengthen the defense by incorporating adversarial
visual instruction tuning. The resulting models from each stage, \\(\Delta\\)CLIP
and \\(\Delta^2\\)LLaVA, show substantially enhanced zero-shot robustness and set a
new state-of-the-art in adversarial defense for vision-language models. For
example, the adversarial robustness of \\(\Delta\\)CLIP surpasses that of the
previous best models on ImageNet-1k by ~20%. %For example, \\(\Delta\\)CLIP
surpasses the previous best models on ImageNet-1k by ~20% in terms of
adversarial robustness. Similarly, compared to prior art, \\(\Delta^2\\)LLaVA
brings a ~30% robustness improvement to image captioning task and a ~20%
robustness improvement to visual question answering task. Furthermore, our
models exhibit stronger zero-shot recognition capability, fewer hallucinations,
and superior reasoning performance compared to baselines. Our project page is
https://doublevisualdefense.github.io/.