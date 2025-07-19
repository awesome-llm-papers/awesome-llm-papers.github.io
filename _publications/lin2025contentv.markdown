---
layout: publication
title: 'Contentv: Efficient Training Of Video Generation Models With Limited Compute'
authors: Lin et al.
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2025
bibkey: lin2025contentv
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.05343'}]
tags: [RAG, ICCV, Training Techniques, Prompting, Agentic, Tools, Model Architecture,
  Efficiency And Optimization, Reinforcement Learning]
---
Recent advances in video generation demand increasingly efficient training recipes to mitigate escalating computational costs. In this report, we present ContentV, an 8B-parameter text-to-video model that achieves state-of-the-art performance (85.14 on VBench) after training on 256 x 64GB Neural Processing Units (NPUs) for merely four weeks. ContentV generates diverse, high-quality videos across multiple resolutions and durations from text prompts, enabled by three key innovations: (1) A minimalist architecture that maximizes reuse of pre-trained image generation models for video generation; (2) A systematic multi-stage training strategy leveraging flow matching for enhanced efficiency; and (3) A cost-effective reinforcement learning with human feedback framework that improves generation quality without requiring additional human annotations. All the code and models are available at: https://contentv.github.io.