---
layout: publication
title: 'MMMG: A Massive, Multidisciplinary, Multi-tier Generation Benchmark For Text-to-image
  Reasoning'
authors: Luo et al.
conference: Proceedings of the 17th Conference of the European Chapter of the Association
  for Computational Linguistics
year: 2025
bibkey: luo2025mmmg
citations: 134
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.10963'}]
tags: [Model Architecture, Prompting, Merging, Datasets, Evaluation, ACL, GPT, Multimodal
    Models, EACL, Reinforcement Learning]
---
In this paper, we introduce knowledge image generation as a new task, alongside the Massive Multi-Discipline Multi-Tier Knowledge-Image Generation Benchmark (MMMG) to probe the reasoning capability of image generation models. Knowledge images have been central to human civilization and to the mechanisms of human learning -- a fact underscored by dual-coding theory and the picture-superiority effect. Generating such images is challenging, demanding multimodal reasoning that fuses world knowledge with pixel-level grounding into clear explanatory visuals. To enable comprehensive evaluation, MMMG offers 4,456 expert-validated (knowledge) image-prompt pairs spanning 10 disciplines, 6 educational levels, and diverse knowledge formats such as charts, diagrams, and mind maps. To eliminate confounding complexity during evaluation, we adopt a unified Knowledge Graph (KG) representation. Each KG explicitly delineates a target image's core entities and their dependencies. We further introduce MMMG-Score to evaluate generated knowledge images. This metric combines factual fidelity, measured by graph-edit distance between KGs, with visual clarity assessment. Comprehensive evaluations of 16 state-of-the-art text-to-image generation models expose serious reasoning deficits -- low entity fidelity, weak relations, and clutter -- with GPT-4o achieving an MMMG-Score of only 50.20, underscoring the benchmark's difficulty. To spur further progress, we release FLUX-Reason (MMMG-Score of 34.45), an effective and open baseline that combines a reasoning LLM with diffusion models and is trained on 16,000 curated knowledge image-prompt pairs.