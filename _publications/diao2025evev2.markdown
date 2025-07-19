---
layout: publication
title: 'Evev2: Improved Baselines For Encoder-free Vision-language Models'
authors: Diao et al.
conference: Computational Visual Media
year: 2025
bibkey: diao2025evev2
citations: 1358
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.06788'}]
tags: [Training Techniques, Tools, Evaluation, Model Architecture, Efficiency And
    Optimization, Reinforcement Learning, Multimodal Models]
---
Existing encoder-free vision-language models (VLMs) are rapidly narrowing the
performance gap with their encoder-based counterparts, highlighting the
promising potential for unified multimodal systems with structural simplicity
and efficient deployment. We systematically clarify the performance gap between
VLMs using pre-trained vision encoders, discrete tokenizers, and minimalist
visual layers from scratch, deeply excavating the under-examined
characteristics of encoder-free VLMs. We develop efficient strategies for
encoder-free VLMs that rival mainstream encoder-based ones. After an in-depth
investigation, we launch EVEv2.0, a new and improved family of encoder-free
VLMs. We show that: (i) Properly decomposing and hierarchically associating
vision and language within a unified model reduces interference between
modalities. (ii) A well-designed training strategy enables effective
optimization for encoder-free VLMs. Through extensive evaluation, our EVEv2.0
represents a thorough study for developing a decoder-only architecture across
modalities, demonstrating superior data efficiency and strong vision-reasoning
capability. Code is publicly available at: https://github.com/baaivision/EVE.