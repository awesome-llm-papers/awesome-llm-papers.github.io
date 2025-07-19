---
layout: publication
title: 'Singleinsert: Inserting New Concepts From A Single Image Into Text-to-image
  Models For Flexible Editing'
authors: Wu et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: wu2023singleinsert
citations: 89
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.08094'}]
tags: [CVPR, Prompting, Training Techniques, Evaluation]
---
Recent progress in text-to-image (T2I) models enables high-quality image
generation with flexible textual control. To utilize the abundant visual priors
in the off-the-shelf T2I models, a series of methods try to invert an image to
proper embedding that aligns with the semantic space of the T2I model. However,
these image-to-text (I2T) inversion methods typically need multiple source
images containing the same concept or struggle with the imbalance between
editing flexibility and visual fidelity. In this work, we point out that the
critical problem lies in the foreground-background entanglement when learning
an intended concept, and propose a simple and effective baseline for
single-image I2T inversion, named SingleInsert. SingleInsert adopts a two-stage
scheme. In the first stage, we regulate the learned embedding to concentrate on
the foreground area without being associated with the irrelevant background. In
the second stage, we finetune the T2I model for better visual resemblance and
devise a semantic loss to prevent the language drift problem. With the proposed
techniques, SingleInsert excels in single concept generation with high visual
fidelity while allowing flexible editing. Additionally, SingleInsert can
perform single-image novel view synthesis and multiple concepts composition
without requiring joint training. To facilitate evaluation, we design an
editing prompt list and introduce a metric named Editing Success Rate (ESR) for
quantitative assessment of editing flexibility. Our project page is:
https://jarrentwu1031.github.io/SingleInsert-web/