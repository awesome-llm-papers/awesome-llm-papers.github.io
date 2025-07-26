---
layout: publication
title: 'Omg-llava: Bridging Image-level, Object-level, Pixel-level Reasoning And Understanding'
authors: Tao Zhang, Xiangtai Li, Hao Fei, Haobo Yuan, Shengqiong Wu, Shunping Ji,
  Chen Change Loy, Shuicheng Yan
conference: No Venue
year: 2024
bibkey: zhang2024omg
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/667e26bfb0f62e5e076bc5b6'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2406.19389'}]
tags: ["Tools"]
short_authors: Zhang et al.
---
Current universal segmentation methods demonstrate strong capabilities in pixel-level image and video understanding. However, they lack reasoning abilities and cannot be controlled via text instructions. In contrast, large vision-language multimodal models exhibit powerful vision-based conversation and reasoning capabilities but lack pixel-level understanding and have difficulty accepting visual prompts for flexible user interaction. This paper proposes OMG-LLaVA, a new and elegant framework combining powerful pixel-level vision understanding with reasoning abilities. It can accept various visual and text prompts for flexible user interaction. Specifically, we use a universal segmentation method as the visual encoder, integrating image information, perception priors, and visual prompts into visual tokens provided to the LLM. The LLM is responsible for understanding the user's text instructions and providing text responses and pixel-level segmentation results based on the visual information. We propose perception prior embedding to better integrate perception priors with image features. OMG-LLaVA achieves image-level, object-level, and pixel-level reasoning and understanding in a single model, matching or surpassing the performance of specialized methods on multiple benchmarks. Rather than using LLM to connect each specialist, our work aims at end-to-end training on one encoder, one decoder, and one LLM. The code and model have been released for further research.

https://huggingface.co/discussions/paper/667e26bfb0f62e5e076bc5b6