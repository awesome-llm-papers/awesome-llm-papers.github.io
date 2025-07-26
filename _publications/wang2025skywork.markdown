---
layout: publication
title: 'Skywork-vl Reward: An Effective Reward Model For Multimodal Understanding
  And Reasoning'
authors: Xiaokun Wang, Chris, Jiangbo Pei, Wei Shen, Yi Peng, Yunzhuo Hao, Weijie
  Qiu, Ai Jian, Tianyidan Xie, Xuchen Song, Yang Liu, Yahui Zhou
conference: No Venue
year: 2025
bibkey: wang2025skywork
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.07263'}]
tags: ["Evaluation", "Model Architecture", "Reinforcement Learning"]
short_authors: Wang et al.
---
We propose Skywork-VL Reward, a multimodal reward model that provides reward signals for both multimodal understanding and reasoning tasks. Our technical approach comprises two key components: First, we construct a large-scale multimodal preference dataset that covers a wide range of tasks and scenarios, with responses collected from both standard vision-language models (VLMs) and advanced VLM reasoners. Second, we design a reward model architecture based on Qwen2.5-VL-7B-Instruct, integrating a reward head and applying multi-stage fine-tuning using pairwise ranking loss on pairwise preference data. Experimental evaluations show that Skywork-VL Reward achieves state-of-the-art results on multimodal VL-RewardBench and exhibits competitive performance on the text-only RewardBench benchmark. Furthermore, preference data constructed based on our Skywork-VL Reward proves highly effective for training Mixed Preference Optimization (MPO), leading to significant improvements in multimodal reasoning capabilities. Our results underscore Skywork-VL Reward as a significant advancement toward general-purpose, reliable reward models for multimodal alignment. Our model has been publicly released to promote transparency and reproducibility.

https://huggingface.co/discussions/paper/6822cf4d3b7392637edd75a5