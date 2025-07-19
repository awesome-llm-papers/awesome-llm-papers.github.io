---
layout: publication
title: 'Versavid-r1: A Versatile Video Understanding And Reasoning Model From Question
  Answering To Captioning Tasks'
authors: Chen et al.
conference: IEEE Transactions on Image Processing
year: 2025
bibkey: chen2025versavid
citations: 72
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.09079'}]
tags: [RAG, Training Techniques, Agentic, Evaluation, Reinforcement Learning, Multimodal
    Models, Datasets]
---
Recent advancements in multimodal large language models have successfully extended the Reason-Then-Respond paradigm to image-based reasoning, yet video-based reasoning remains an underdeveloped frontier, primarily due to the scarcity of high-quality reasoning-oriented data and effective training methodologies. To bridge this gap, we introduce DarkEventInfer and MixVidQA, two novel datasets specifically designed to stimulate the model's advanced video understanding and reasoning abilities. DarkEventinfer presents videos with masked event segments, requiring models to infer the obscured content based on contextual video cues. MixVidQA, on the other hand, presents interleaved video sequences composed of two distinct clips, challenging models to isolate and reason about one while disregarding the other. Leveraging these carefully curated training samples together with reinforcement learning guided by diverse reward functions, we develop VersaVid-R1, the first versatile video understanding and reasoning model under the Reason-Then-Respond paradigm capable of handling multiple-choice and open-ended question answering, as well as video captioning tasks. Extensive experiments demonstrate that VersaVid-R1 significantly outperforms existing models across a broad spectrum of benchmarks, covering video general understanding, cognitive reasoning, and captioning tasks.