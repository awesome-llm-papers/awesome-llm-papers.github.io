---
layout: publication
title: 'Uniqa: Unified Vision-language Pre-training For Image Quality And Aesthetic
  Assessment'
authors: Zhou et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2024
bibkey: zhou2024uniqa
citations: 472
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.01069'}]
tags: [Training Techniques, Reinforcement Learning, Multimodal Models, AAAI, Datasets]
---
Image Quality Assessment (IQA) and Image Aesthetic Assessment (IAA) aim to
simulate human subjective perception of image visual quality and aesthetic
appeal. Existing methods typically address these tasks independently due to
distinct learning objectives. However, they neglect the underlying
interconnectedness of both tasks, which hinders the learning of task-agnostic
shared representations for human subjective perception. To confront this
challenge, we propose Unified vision-language pre-training of Quality and
Aesthetics (UniQA), to learn general perceptions of two tasks, thereby
benefiting them simultaneously. Addressing the absence of text in the IQA
datasets and the presence of textual noise in the IAA datasets, (1) we utilize
multimodal large language models (MLLMs) to generate high-quality text
descriptions; (2) the generated text for IAA serves as metadata to purify noisy
IAA data. To effectively adapt the pre-trained UniQA to downstream tasks, we
further propose a lightweight adapter that utilizes versatile cues to fully
exploit the extensive knowledge of the pre-trained model. Extensive experiments
demonstrate that our approach attains a new state-of-the-art performance on
both IQA and IAA tasks, while concurrently showcasing exceptional zero-shot and
few-label image assessment capabilities. The source code will be available at
https://github.com/zht8506/UniQA.