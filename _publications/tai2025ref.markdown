---
layout: publication
title: 'REF-VLM: Triplet-based Referring Paradigm For Unified Visual Decoding'
authors: Tai et al.
conference: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: tai2025ref
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.07413'}]
tags: [Interpretability And Explainability, Training Techniques, Prompting, Tools,
  CVPR, Evaluation, Multimodal Models, Datasets]
---
Multimodal Large Language Models (MLLMs) demonstrate robust zero-shot
capabilities across diverse vision-language tasks after training on mega-scale
datasets. However, dense prediction tasks, such as semantic segmentation and
keypoint detection, pose significant challenges for MLLMs when represented
solely as text outputs. Simultaneously, current MLLMs utilizing latent
embeddings for visual task decoding generally demonstrate limited adaptability
to both multi-task learning and multi-granularity scenarios. In this work, we
present REF-VLM, an end-to-end framework for unified training of various visual
decoding tasks. To address complex visual decoding scenarios, we introduce the
Triplet-Based Referring Paradigm (TRP), which explicitly decouples three
critical dimensions in visual decoding tasks through a triplet structure:
concepts, decoding types, and targets. TRP employs symbolic delimiters to
enforce structured representation learning, enhancing the parsability and
interpretability of model outputs. Additionally, we construct Visual-Task
Instruction Following Dataset (VTInstruct), a large-scale multi-task dataset
containing over 100 million multimodal dialogue samples across 25 task types.
Beyond text inputs and outputs, VT-Instruct incorporates various visual prompts
such as point, box, scribble, and mask, and generates outputs composed of text
and visual units like box, keypoint, depth and mask. The combination of
different visual prompts and visual units generates a wide variety of task
types, expanding the applicability of REF-VLM significantly. Both qualitative
and quantitative experiments demonstrate that our REF-VLM outperforms other
MLLMs across a variety of standard benchmarks. The code, dataset, and demo
available at https://github.com/MacavityT/REF-VLM.