---
layout: publication
title: Mitigating Object Hallucination Via Robust Local Perception Search
authors: Gao et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2023'
year: 2025
bibkey: gao2025mitigating
citations: 92
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.06729'}]
tags: [Training Techniques, Evaluation, ACL, EMNLP, RAG, Multimodal Models, Datasets,
  Reinforcement Learning]
---
Recent advancements in Multimodal Large Language Models (MLLMs) have enabled them to effectively integrate vision and language, addressing a variety of downstream tasks. However, despite their significant success, these models still exhibit hallucination phenomena, where the outputs appear plausible but do not align with the content of the images. To mitigate this issue, we introduce Local Perception Search (LPS), a decoding method during inference that is both simple and training-free, yet effectively suppresses hallucinations. This method leverages local visual prior information as a value function to correct the decoding process. Additionally, we observe that the impact of the local visual prior on model performance is more pronounced in scenarios with high levels of image noise. Notably, LPS is a plug-and-play approach that is compatible with various models. Extensive experiments on widely used hallucination benchmarks and noisy data demonstrate that LPS significantly reduces the incidence of hallucinations compared to the baseline, showing exceptional performance, particularly in noisy settings.