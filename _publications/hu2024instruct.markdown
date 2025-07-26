---
layout: publication
title: 'Instruct-imagen: Image Generation With Multi-modal Instruction'
authors: Hexiang Hu, Kelvin C. K. Chan, Yu-chuan Su, Wenhu Chen, Yandong Li, Kihyuk
  Sohn, Yang Zhao, Xue Ben, Boqing Gong, William Cohen, Ming-wei Chang, Xuhui Jia
conference: No Venue
year: 2024
bibkey: hu2024instruct
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2401.01952'}]
tags: ["Datasets", "Evaluation", "Fine-Tuning", "RAG", "Tools", "Training Techniques"]
short_authors: Hu et al.
---
This paper presents instruct-imagen, a model that tackles heterogeneous image generation tasks and generalizes across unseen tasks. We introduce *multi-modal instruction* for image generation, a task representation articulating a range of generation intents with precision. It uses natural language to amalgamate disparate modalities (e.g., text, edge, style, subject, etc.), such that abundant generation intents can be standardized in a uniform format. We then build instruct-imagen by fine-tuning a pre-trained text-to-image diffusion model with a two-stage framework. First, we adapt the model using the retrieval-augmented training, to enhance model's capabilities to ground its generation on external multimodal context. Subsequently, we fine-tune the adapted model on diverse image generation tasks that requires vision-language understanding (e.g., subject-driven generation, etc.), each paired with a multi-modal instruction encapsulating the task's essence. Human evaluation on various image generation datasets reveals that instruct-imagen matches or surpasses prior task-specific models in-domain and demonstrates promising generalization to unseen and more complex tasks.

https://huggingface.co/discussions/paper/659772f7ce6e887177e46044