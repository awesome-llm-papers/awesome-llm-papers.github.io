---
layout: publication
title: 'Visionthink: Smart And Efficient Vision Language Model Via Reinforcement Learning'
authors: Senqiao Yang, Junyi Li, Xin Lai, Bei Yu, Hengshuang Zhao, Jiaya Jia
conference: No Venue
year: 2025
bibkey: yang2025visionthink
additional_links: [{name: Code, url: 'https://github.com/dvlab-research/VisionThink'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/6879ba2121b37e676c8e40cf'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2507.13348'}]
tags: ["Efficiency", "Reinforcement Learning"]
short_authors: Yang et al.
---
Recent advancements in vision-language models (VLMs) have improved performance by increasing the number of visual tokens, which are often significantly longer than text tokens. However, we observe that most real-world scenarios do not require such an extensive number of visual tokens. While the performance drops significantly in a small subset of OCR-related tasks, models still perform accurately in most other general VQA tasks with only 1/4 resolution. Therefore, we propose to dynamically process distinct samples with different resolutions, and present a new paradigm for visual token compression, namely, VisionThink. It starts with a downsampled image and smartly decides whether it is sufficient for problem solving. Otherwise, the model could output a special token to request the higher-resolution image. Compared to existing Efficient VLM methods that compress tokens using fixed pruning ratios or thresholds, VisionThink autonomously decides whether to compress tokens case by case. As a result, it demonstrates strong fine-grained visual understanding capability on OCR-related tasks, and meanwhile saves substantial visual tokens on simpler tasks. We adopt reinforcement learning and propose the LLM-as-Judge strategy to successfully apply RL to general VQA tasks. Moreover, we carefully design a reward function and penalty mechanism to achieve a stable and reasonable image resize call ratio. Extensive experiments demonstrate the superiority, efficiency, and effectiveness of our method. Our code is available at https://github.com/dvlab-research/VisionThink.

https://huggingface.co/discussions/paper/6879ba2121b37e676c8e40cf