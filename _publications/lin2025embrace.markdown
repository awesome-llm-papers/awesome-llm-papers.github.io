---
layout: publication
title: 'Embrace-3k: Embodied Reasoning And Action In Complex Environments'
authors: Mingxian Lin, Wei Huang, Yitang Li, Chengjie Jiang, Kui Wu, Fangwei Zhong,
  Shengju Qian, Xin Wang, Xiaojuan Qi
conference: No Venue
year: 2025
bibkey: lin2025embrace
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2507.10548'}]
tags: ["Agentic", "Datasets", "Evaluation", "Model Architecture", "Reinforcement Learning", "Tools"]
short_authors: Lin et al.
---
Recent advanced vision-language models(VLMs) have demonstrated strong performance on passive, offline image and video understanding tasks. However, their effectiveness in embodied settings, which require online interaction and active scene understanding remains limited. In such scenarios, an agent perceives the environment from a first-person perspective, with each action dynamically shaping subsequent observations. Even state-of-the-art models such as GPT-4o, Claude 3.5 Sonnet, and Gemini 2.5 Pro struggle in open-environment interactions, exhibiting clear limitations in spatial reasoning and long-horizon planning. To address this gap, we introduce EmRACE-3K, a dataset of over 3,000 language-guided tasks situated in diverse, photorealistic environments constructed using Unreal Engine and the UnrealCV-Zoo framework. The tasks encompass a wide range of embodied challenges, including navigation, object manipulation, and multi-stage goal execution. Each task unfolds as a multi-step trajectory, pairing first-person visual observations with high-level instructions, grounded actions, and natural language rationales that express the agent's intent at every step. Using EmRACE-3K, we establish a benchmark to evaluate the embodied reasoning capabilities of VLMs across three key dimensions: Exploration, Dynamic Spatial-Semantic Reasoning, and Multi-stage Goal Execution. In zero-shot settings, all models achieve success rates below 20%, underscoring the challenge posed by our benchmark and the current limitations of VLMs in interactive environments. To demonstrate the utility of EmRACE-3K, we further fine-tune Qwen2.5-VL-7B using supervised learning followed by reinforcement learning. This approach yields substantial improvements across all three challenge categories, highlighting the dataset's effectiveness in enabling the development of embodied reasoning capabilities.

https://huggingface.co/discussions/paper/6875d6e7257d4f04353705be