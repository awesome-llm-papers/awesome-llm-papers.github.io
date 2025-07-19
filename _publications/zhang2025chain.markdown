---
layout: publication
title: 'Chain-of-focus: Adaptive Visual Search And Zooming For Multimodal Reasoning
  Via RL'
authors: Zhang et al.
conference: IEEE Transactions on Cybernetics
year: 2025
bibkey: zhang2025chain
citations: 78
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.15436'}]
tags: [Training Techniques, Fine Tuning, Evaluation, Agentic, Applications, RAG, Ethics
    and Bias, Multimodal Models, Datasets, Reinforcement Learning]
---
Vision language models (VLMs) have achieved impressive performance across a variety of computer vision tasks. However, the multimodal reasoning capability has not been fully explored in existing models. In this paper, we propose a Chain-of-Focus (CoF) method that allows VLMs to perform adaptive focusing and zooming in on key image regions based on obtained visual cues and the given questions, achieving efficient multimodal reasoning. To enable this CoF capability, we present a two-stage training pipeline, including supervised fine-tuning (SFT) and reinforcement learning (RL). In the SFT stage, we construct the MM-CoF dataset, comprising 3K samples derived from a visual agent designed to adaptively identify key regions to solve visual tasks with different image resolutions and questions. We use MM-CoF to fine-tune the Qwen2.5-VL model for cold start. In the RL stage, we leverage the outcome accuracies and formats as rewards to update the Qwen2.5-VL model, enabling further refining the search and reasoning strategy of models without human priors. Our model achieves significant improvements on multiple benchmarks. On the V* benchmark that requires strong visual reasoning capability, our model outperforms existing VLMs by 5% among 8 image resolutions ranging from 224 to 4K, demonstrating the effectiveness of the proposed CoF method and facilitating the more efficient deployment of VLMs in practical applications.