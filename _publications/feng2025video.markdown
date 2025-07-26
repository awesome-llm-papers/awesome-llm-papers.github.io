---
layout: publication
title: 'Video-r1: Reinforcing Video Reasoning In Mllms'
authors: Kaituo Feng, Kaixiong Gong, Bohao Li, Zonghao Guo, Yibing Wang, Tianshuo
  Peng, Benyou Wang, Xiangyu Yue
conference: No Venue
year: 2025
bibkey: feng2025video
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67e6090348742d6df75853de'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2503.21776'}]
tags: ["Datasets", "Evaluation", "Fine-Tuning", "Model Architecture", "Prompting", "Reinforcement Learning", "Time Series", "Training Techniques"]
short_authors: Feng et al.
---
Inspired by DeepSeek-R1's success in eliciting reasoning abilities through rule-based reinforcement learning (RL), we introduce Video-R1 as the first attempt to systematically explore the R1 paradigm for eliciting video reasoning within multimodal large language models (MLLMs). However, directly applying RL training with the GRPO algorithm to video reasoning presents two primary challenges: (i) a lack of temporal modeling for video reasoning, and (ii) the scarcity of high-quality video-reasoning data. To address these issues, we first propose the T-GRPO algorithm, which encourages models to utilize temporal information in videos for reasoning. Additionally, instead of relying solely on video data, we incorporate high-quality image-reasoning data into the training process. We have constructed two datasets: Video-R1-COT-165k for SFT cold start and Video-R1-260k for RL training, both comprising image and video data. Experimental results demonstrate that Video-R1 achieves significant improvements on video reasoning benchmarks such as VideoMMMU and VSI-Bench, as well as on general video benchmarks including MVBench and TempCompass, etc. Notably, Video-R1-7B attains a 35.8% accuracy on video spatial reasoning benchmark VSI-bench, surpassing the commercial proprietary model GPT-4o. All codes, models, data are released.

https://huggingface.co/discussions/paper/67e6090348742d6df75853de