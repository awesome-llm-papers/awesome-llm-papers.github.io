---
layout: publication
title: 'Grid: Omni Visual Generation'
authors: Wan et al.
conference: Image and Vision Computing
year: 2024
bibkey: wan2024grid
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.10718'}]
tags: [RAG, Training Techniques]
---
Visual generation has witnessed remarkable progress in single-image tasks, yet extending these capabilities to temporal sequences remains challenging. Current approaches either build specialized video models from scratch with enormous computational costs or add separate motion modules to image generators, both requiring learning temporal dynamics anew. We observe that modern image generation models possess underutilized potential in handling structured layouts with implicit temporal understanding. Building on this insight, we introduce GRID, which reformulates temporal sequences as grid layouts, enabling holistic processing of visual sequences while leveraging existing model capabilities. Through a parallel flow-matching training strategy with coarse-to-fine scheduling, our approach achieves up to 67 faster inference speeds while using <1/1000 of the computational resources compared to specialized models. Extensive experiments demonstrate that GRID not only excels in temporal tasks from Text-to-Video to 3D Editing but also preserves strong performance in image generation, establishing itself as an efficient and versatile omni-solution for visual generation.