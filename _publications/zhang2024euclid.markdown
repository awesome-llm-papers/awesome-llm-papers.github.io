---
layout: publication
title: 'Euclid: Supercharging Multimodal Llms With Synthetic High-fidelity Visual
  Descriptions'
authors: Jiarui Zhang, Ollie Liu, Tianyu Yu, Jinyi Hu, Willie Neiswanger
conference: No Venue
year: 2024
bibkey: zhang2024euclid
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2412.08737'}]
tags: ["Applications", "Model Architecture", "Training Techniques"]
short_authors: Zhang et al.
---
Multimodal large language models (MLLMs) have made rapid progress in recent years, yet continue to struggle with low-level visual perception (LLVP) -- particularly the ability to accurately describe the geometric details of an image. This capability is crucial for applications in areas such as robotics, medical image analysis, and manufacturing. In this paper, we first introduce Geoperception, a benchmark designed to evaluate an MLLM's ability to accurately transcribe 2D geometric information from an image. Using this benchmark, we demonstrate the limitations of leading MLLMs, and then conduct a comprehensive empirical study to explore strategies for improving their performance on geometric tasks. Our findings highlight the benefits of certain model architectures, training techniques, and data strategies, including the use of high-fidelity synthetic data and multi-stage training with a data curriculum. Notably, we find that a data curriculum enables models to learn challenging geometry understanding tasks which they fail to learn from scratch. Leveraging these insights, we develop Euclid, a family of models specifically optimized for strong low-level geometric perception. Although purely trained on synthetic multimodal data, Euclid shows strong generalization ability to novel geometry shapes. For instance, Euclid outperforms the best closed-source model, Gemini-1.5-Pro, by up to 58.56% on certain Geoperception benchmark tasks and 10.65% on average across all tasks.

https://huggingface.co/discussions/paper/675bac3248fca25a2189e688