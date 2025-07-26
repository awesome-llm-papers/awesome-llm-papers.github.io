---
layout: publication
title: 'Dispider: Enabling Video Llms With Active Real-time Interaction Via Disentangled
  Perception, Decision, And Reaction'
authors: Rui Qian, Shuangrui Ding, Xiaoyi Dong, Pan Zhang, Yuhang Zang, Yuhang Cao,
  Dahua Lin, Jiaqi Wang
conference: No Venue
year: 2025
bibkey: qian2025dispider
additional_links: [{name: Code, url: 'https://github.com/Mark12Ding/Dispider'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/677cdc014804091804c6552e'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2501.03218'}]
tags: ["Has Code", "Model Architecture"]
short_authors: Qian et al.
---
Active Real-time interaction with video LLMs introduces a new paradigm for human-computer interaction, where the model not only understands user intent but also responds while continuously processing streaming video on the fly. Unlike offline video LLMs, which analyze the entire video before answering questions, active real-time interaction requires three capabilities: 1) Perception: real-time video monitoring and interaction capturing. 2) Decision: raising proactive interaction in proper situations, 3) Reaction: continuous interaction with users. However, inherent conflicts exist among the desired capabilities. The Decision and Reaction require a contrary Perception scale and grain, and the autoregressive decoding blocks the real-time Perception and Decision during the Reaction. To unify the conflicted capabilities within a harmonious system, we present Dispider, a system that disentangles Perception, Decision, and Reaction. Dispider features a lightweight proactive streaming video processing module that tracks the video stream and identifies optimal moments for interaction. Once the interaction is triggered, an asynchronous interaction module provides detailed responses, while the processing module continues to monitor the video in the meantime. Our disentangled and asynchronous design ensures timely, contextually accurate, and computationally efficient responses, making Dispider ideal for active real-time interaction for long-duration video streams. Experiments show that Dispider not only maintains strong performance in conventional video QA tasks, but also significantly surpasses previous online models in streaming scenario responses, thereby validating the effectiveness of our architecture. The code and model are released at https://github.com/Mark12Ding/Dispider.

https://huggingface.co/discussions/paper/677cdc014804091804c6552e