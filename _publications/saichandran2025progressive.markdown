---
layout: publication
title: Progressive Prompt Detailing For Improved Alignment In Text-to-image Generative
  Models
authors: Saichandran et al.
conference: CHI Conference on Human Factors in Computing Systems
year: 2025
bibkey: saichandran2025progressive
citations: 312
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.17794'}]
tags: [RAG, Training Techniques, Prompting, Datasets, Merging]
---
Text-to-image generative models often struggle with long prompts detailing complex scenes, diverse objects with distinct visual characteristics and spatial relationships. In this work, we propose SCoPE (Scheduled interpolation of Coarse-to-fine Prompt Embeddings), a training-free method to improve text-to-image alignment by progressively refining the input prompt in a coarse-to-fine-grained manner. Given a detailed input prompt, we first decompose it into multiple sub-prompts which evolve from describing broad scene layout to highly intricate details. During inference, we interpolate between these sub-prompts and thus progressively introduce finer-grained details into the generated image. Our training-free plug-and-play approach significantly enhances prompt alignment, achieves an average improvement of more than +8 in Visual Question Answering (VQA) scores over the Stable Diffusion baselines on 83% of the prompts from the GenAI-Bench dataset.