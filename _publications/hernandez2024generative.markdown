---
layout: publication
title: Generative Visual Instruction Tuning
authors: Hernandez Jefferson, Villegas Ruben, Ordonez Vicente
conference: 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: hernandez2024generative
citations: 337
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.11262'}]
tags: [GPT, CVPR, Model Architecture, Language Modeling, Reinforcement Learning, Multimodal
    Models, Datasets, Merging]
---
We propose to use automatically generated instruction-following data to
improve the zero-shot capabilities of a large multimodal model with additional
support for generative and image editing tasks. We achieve this by curating a
new multimodal instruction-following set using GPT-4V and existing datasets for
image generation and editing. Using this instruction set and the existing
LLaVA-Finetune instruction set for visual understanding tasks, we produce
GenLLaVA, a Generative Large Language and Visual Assistant. GenLLaVA is built
through a strategy that combines three types of large pretrained models through
instruction finetuning: Mistral for language modeling, SigLIP for image-text
matching, and StableDiffusion for text-to-image generation. Our model
demonstrates visual understanding capabilities superior to LLaVA and
additionally demonstrates competitive results with native multimodal models
such as Unified-IO 2, paving the way for building advanced general-purpose
visual assistants by effectively re-using existing multimodal models. We
open-source our dataset, codebase, and model checkpoints to foster further
research and application in this domain.