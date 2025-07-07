---
layout: publication
title: 'Minigpt-v2: Large Language Model As A Unified Interface For Vision-language
  Multi-task Learning'
authors: Jun Chen et al.
conference: Arxiv
year: 2023
citations: 46
bibkey: chen2023minigpt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.09478'}, {name: Code,
    url: 'https://minigpt-v2.github.io/'}]
tags: [Training Techniques, GPT, Efficiency and Optimization, Has Code, Applications,
  Multimodal Models, Model Architecture]
---
Large language models have shown their remarkable capabilities as a general
interface for various language-related applications. Motivated by this, we
target to build a unified interface for completing many vision-language tasks
including image description, visual question answering, and visual grounding,
among others. The challenge is to use a single model for performing diverse
vision-language tasks effectively with simple multi-modal instructions. Towards
this objective, we introduce MiniGPT-v2, a model that can be treated as a
unified interface for better handling various vision-language tasks. We propose
using unique identifiers for different tasks when training the model. These
identifiers enable our model to better distinguish each task instruction
effortlessly and also improve the model learning efficiency for each task.
After the three-stage training, the experimental results show that MiniGPT-v2
achieves strong performance on many visual question-answering and visual
grounding benchmarks compared to other vision-language generalist models. Our
model and codes are available at https://minigpt-v2.github.io/