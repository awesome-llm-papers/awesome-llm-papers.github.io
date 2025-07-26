---
layout: publication
title: 'E5-V: Universal Embeddings With Multimodal Large Language Models'
authors: Ting Jiang, Minghui Song, Zihan Zhang, Haizhen Huang, Weiwei Deng, Feng Sun,
  Qi Zhang, Deqing Wang, Fuzhen Zhuang
conference: No Venue
year: 2024
bibkey: jiang2024e5
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2407.12580'}]
tags: ["Datasets", "Fine-Tuning", "Tools", "Training Techniques"]
short_authors: Jiang et al.
---
Multimodal large language models (MLLMs) have shown promising advancements in general visual and language understanding. However, the representation of multimodal information using MLLMs remains largely unexplored. In this work, we introduce a new framework, E5-V, designed to adapt MLLMs for achieving universal multimodal embeddings. Our findings highlight the significant potential of MLLMs in representing multimodal inputs compared to previous approaches. By leveraging MLLMs with prompts, E5-V effectively bridges the modality gap between different types of inputs, demonstrating strong performance in multimodal embeddings even without fine-tuning. We propose a single modality training approach for E5-V, where the model is trained exclusively on text pairs. This method demonstrates significant improvements over traditional multimodal training on image-text pairs, while reducing training costs by approximately 95%. Additionally, this approach eliminates the need for costly multimodal training data collection. Extensive experiments across four types of tasks demonstrate the effectiveness of E5-V. As a universal multimodal model, E5-V not only achieves but often surpasses state-of-the-art performance in each task, despite being trained on a single modality.

https://huggingface.co/discussions/paper/66987f3cbc2f8c7459128c4a