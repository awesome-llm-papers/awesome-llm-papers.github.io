---
layout: publication
title: 'Peekaboo: Text To Image Diffusion Models Are Zero-shot Segmentors'
authors: Burgert et al.
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2022
bibkey: burgert2022peekaboo
citations: 187
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.13224'}]
tags: [RAG, ICCV, Training Techniques, Prompting, Ethics And Bias, Efficiency And
    Optimization, Reinforcement Learning, Datasets, Merging]
---
Recently, text-to-image diffusion models have shown remarkable capabilities
in creating realistic images from natural language prompts. However, few works
have explored using these models for semantic localization or grounding. In
this work, we explore how an off-the-shelf text-to-image diffusion model,
trained without exposure to localization information, can ground various
semantic phrases without segmentation-specific re-training. We introduce an
inference time optimization process capable of generating segmentation masks
conditioned on natural language prompts. Our proposal, Peekaboo, is a
first-of-its-kind zero-shot, open-vocabulary, unsupervised semantic grounding
technique leveraging diffusion models without any training. We evaluate
Peekaboo on the Pascal VOC dataset for unsupervised semantic segmentation and
the RefCOCO dataset for referring segmentation, showing results competitive
with promising results. We also demonstrate how Peekaboo can be used to
generate images with transparency, even though the underlying diffusion model
was only trained on RGB images - which to our knowledge we are the first to
attempt. Please see our project page, including our code:
https://ryanndagreat.github.io/peekaboo