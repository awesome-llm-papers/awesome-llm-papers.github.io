---
layout: publication
title: Diving Into Self-evolving Training For Multimodal Reasoning
authors: Wei Liu, Junlong Li, Xiwen Zhang, Fan Zhou, Yu Cheng, Junxian He
conference: No Venue
year: 2024
bibkey: liu2024diving
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2412.17451'}]
tags: ["Training Techniques"]
short_authors: Liu et al.
---
Reasoning ability is essential for Large Multimodal Models (LMMs). In the absence of multimodal chain-of-thought annotated data, self-evolving training, where the model learns from its own outputs, has emerged as an effective and scalable approach for enhancing reasoning abilities. Despite its growing usage, a comprehensive understanding of self-evolving training, particularly in the context of multimodal reasoning, remains limited. In this paper, we delve into the intricacies of self-evolving training for multimodal reasoning, pinpointing three key factors: Training Method, Reward Model, and Prompt Variation. We systematically examine each factor and explore how various configurations affect the training's effectiveness. Our analysis leads to a set of best practices for each factor, aimed at optimizing multimodal reasoning. Furthermore, we explore the Self-Evolution Dynamics during training and the impact of automatic balancing mechanisms in boosting performance. After all the investigations, we present a final recipe for self-evolving training in multimodal reasoning, encapsulating these design choices into a framework we call MSTaR (Multimodal Self-evolving Training for Reasoning), which is universally effective for models with different sizes on various benchmarks, e.g., surpassing the pre-evolved model significantly on 5 multimodal reasoning benchmarks without using additional human annotations, as demonstrated on MiniCPM-V-2.5 (8B), Phi-3.5-Vision (4B) and InternVL2 (2B). We believe this study fills a significant gap in the understanding of self-evolving training for multimodal reasoning and offers a robust framework for future research. Our policy and reward models, as well as the collected data, is released to facilitate further investigation in multimodal reasoning.

https://huggingface.co/discussions/paper/676a25e48ffab02f2c91a9e3