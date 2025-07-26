---
layout: publication
title: How Well Does Gpt-4o Understand Vision? Evaluating Multimodal Foundation Models
  On Standard Computer Vision Tasks
authors: "Rahul Ramachandran, Ali Garjani, Roman Bachmann, Andrei Atanov, O\u011F\
  uzhan Fatih Kar, Amir Zamir"
conference: No Venue
year: 2025
bibkey: ramachandran2025how
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2507.01955'}]
tags: ["Evaluation", "Model Architecture"]
short_authors: Ramachandran et al.
---
Multimodal foundation models, such as GPT-4o, have recently made remarkable progress, but it is not clear where exactly these models stand in terms of understanding vision. In this paper, we benchmark the performance of popular multimodal foundation models (GPT-4o, o4-mini, Gemini 1.5 Pro and Gemini 2.0 Flash, Claude 3.5 Sonnet, Qwen2-VL, Llama 3.2) on standard computer vision tasks (semantic segmentation, object detection, image classification, depth and surface normal prediction) using established datasets (e.g., COCO, ImageNet and its variants, etc). The main challenges to performing this are: 1) most models are trained to output text and cannot natively express versatile domains, such as segments or 3D geometry, and 2) many leading models are proprietary and accessible only at an API level, i.e., there is no weight access to adapt them. We address these challenges by translating standard vision tasks into equivalent text-promptable and API-compatible tasks via prompt chaining to create a standardized benchmarking framework. We observe that 1) the models are not close to the state-of-the-art specialist models at any task. However, 2) they are respectable generalists; this is remarkable as they are presumably trained on primarily image-text-based tasks. 3) They perform semantic tasks notably better than geometric ones. 4) While the prompt-chaining techniques affect performance, better models exhibit less sensitivity to prompt variations. 5) GPT-4o performs the best among non-reasoning models, securing the top position in 4 out of 6 tasks, 6) reasoning models, e.g. o3, show improvements in geometric tasks, and 7) a preliminary analysis of models with native image generation, like the latest GPT-4o, shows they exhibit quirks like hallucinations and spatial misalignments.

https://huggingface.co/discussions/paper/686b8348213f123a1f88bdce