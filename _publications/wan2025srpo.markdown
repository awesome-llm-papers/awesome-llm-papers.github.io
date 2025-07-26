---
layout: publication
title: 'SRPO: Enhancing Multimodal LLM Reasoning Via Reflection-aware Reinforcement
  Learning'
authors: Zhongwei Wan, Zhihao Dou, Che Liu, Yu Zhang, Dongfei Cui, Qinjian Zhao, Hui
  Shen, Jing Xiong, Yi Xin, Yifan Jiang, Yangfan He, Mi Zhang, Shen Yan
conference: No Venue
year: 2025
bibkey: wan2025srpo
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.01713'}]
tags: ["Reinforcement Learning"]
short_authors: Wan et al.
---
Multimodal large language models (MLLMs) have shown promising capabilities in reasoning tasks, yet still struggle with complex problems requiring explicit self-reflection and self-correction, especially compared to their unimodal text-based counterparts. Existing reflection methods are simplistic and struggle to generate meaningful and instructive feedback, as the reasoning ability and knowledge limits of pre-trained models are largely fixed during initial training. To overcome these challenges, we propose Multimodal Self-Reflection enhanced reasoning with Group Relative Policy Optimization (SRPO), a two-stage reflection-aware reinforcement learning (RL) framework explicitly designed to enhance multimodal LLM reasoning. In the first stage, we construct a high-quality, reflection-focused dataset under the guidance of an advanced MLLM, which generates reflections based on initial responses to help the policy model learn both reasoning and self-reflection. In the second stage, we introduce a novel reward mechanism within the GRPO framework that encourages concise and cognitively meaningful reflection while avoiding redundancy. Extensive experiments across multiple multimodal reasoning benchmarks, including MathVista, MathVision, MathVerse, and MMMU-Pro, using Qwen-2.5-VL-7B and Qwen-2.5-VL-32B demonstrate that SRPO significantly outperforms state-of-the-art models, achieving notable improvements in both reasoning accuracy and reflection quality.

https://huggingface.co/discussions/paper/683ec81853981b08324ce5f1