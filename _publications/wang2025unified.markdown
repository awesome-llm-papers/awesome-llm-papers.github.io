---
layout: publication
title: A Unified Agentic Framework For Evaluating Conditional Image Generation
authors: Jifang Wang, Xue Yang, Longyue Wang, Zhenran Xu, Yiyu Wang, Yaowei Wang,
  Weihua Luo, Kaifu Zhang, Baotian Hu, Min Zhang
conference: No Venue
year: 2025
bibkey: wang2025unified
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.07046'}]
tags: ["Agentic", "Evaluation"]
short_authors: Wang et al.
---
Conditional image generation has gained significant attention for its ability to personalize content. However, the field faces challenges in developing task-agnostic, reliable, and explainable evaluation metrics. This paper introduces CIGEval, a unified agentic framework for comprehensive evaluation of conditional image generation tasks. CIGEval utilizes large multimodal models (LMMs) as its core, integrating a multi-functional toolbox and establishing a fine-grained evaluation framework. Additionally, we synthesize evaluation trajectories for fine-tuning, empowering smaller LMMs to autonomously select appropriate tools and conduct nuanced analyses based on tool outputs. Experiments across seven prominent conditional image generation tasks demonstrate that CIGEval (GPT-4o version) achieves a high correlation of 0.4625 with human assessments, closely matching the inter-annotator correlation of 0.47. Moreover, when implemented with 7B open-source LMMs using only 2.3K training trajectories, CIGEval surpasses the previous GPT-4o-based state-of-the-art method. Case studies on GPT-4o image generation highlight CIGEval's capability in identifying subtle issues related to subject consistency and adherence to control guidance, indicating its great potential for automating evaluation of image generation tasks with human-level reliability.

https://huggingface.co/discussions/paper/67f7472b353d129fc7c4bf4b