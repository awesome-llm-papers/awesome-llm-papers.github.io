---
layout: publication
title: 'Xtrimopglm: Unified 100b-scale Pre-trained Transformer For Deciphering The
  Language Of Protein'
authors: Chen et al.
conference: Arxiv
year: 2024
bibkey: chen2024xtrimopglm
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2401.06199'}]
tags: [Training Techniques, GPT, Tools, Evaluation, Transformer, Model Architecture,
  Efficiency And Optimization, Fine Tuning, Datasets]
---
Protein language models have shown remarkable success in learning biological
information from protein sequences. However, most existing models are limited
by either autoencoding or autoregressive pre-training objectives, which makes
them struggle to handle protein understanding and generation tasks
concurrently. We propose a unified protein language model, xTrimoPGLM, to
address these two types of tasks simultaneously through an innovative
pre-training framework. Our key technical contribution is an exploration of the
compatibility and the potential for joint optimization of the two types of
objectives, which has led to a strategy for training xTrimoPGLM at an
unprecedented scale of 100 billion parameters and 1 trillion training tokens.
Our extensive experiments reveal that 1) xTrimoPGLM significantly outperforms
other advanced baselines in 18 protein understanding benchmarks across four
categories. The model also facilitates an atomic-resolution view of protein
structures, leading to an advanced 3D structural prediction model that
surpasses existing language model-based tools. 2) xTrimoPGLM not only can
generate de novo protein sequences following the principles of natural ones,
but also can perform programmable generation after supervised fine-tuning (SFT)
on curated sequences. These results highlight the substantial capability and
versatility of xTrimoPGLM in understanding and generating protein sequences,
contributing to the evolving landscape of foundation models in protein science.