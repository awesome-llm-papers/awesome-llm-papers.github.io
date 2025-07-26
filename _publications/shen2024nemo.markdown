---
layout: publication
title: 'Nemo-aligner: Scalable Toolkit For Efficient Model Alignment'
authors: Gerald Shen, Zhilin Wang, Olivier Delalleau, Jiaqi Zeng, Yi Dong, Daniel
  Egert, Shengyang Sun, Jimmy Zhang, Sahil Jain, Ali Taghibakhshi, Markel Sanz Ausin,
  Ashwath Aithal, Oleksii Kuchaiev
conference: No Venue
year: 2024
bibkey: shen2024nemo
additional_links: [{name: Code, url: 'https://github.com/NVIDIA/NeMo-Aligner'}, {
    name: Paper, url: 'https://arxiv.org/abs/hf2405.01481'}]
tags: ["Efficiency", "Has Code", "Tools"]
short_authors: Shen et al.
---
Aligning Large Language Models (LLMs) with human values and preferences is essential for making them helpful and safe. However, building efficient tools to perform alignment can be challenging, especially for the largest and most competent LLMs which often contain tens or hundreds of billions of parameters. We create NeMo-Aligner, a toolkit for model alignment that can efficiently scale to using hundreds of GPUs for training. NeMo-Aligner comes with highly optimized and scalable implementations for major paradigms of model alignment such as: Reinforcement Learning from Human Feedback (RLHF), Direct Preference Optimization (DPO), SteerLM, and Self-Play Fine-Tuning (SPIN). Additionally, our toolkit supports running most of the alignment techniques in a Parameter Efficient Fine-Tuning (PEFT) setting. NeMo-Aligner is designed for extensibility, allowing support for other alignment techniques with minimal effort. It is open-sourced with Apache 2.0 License and we invite community contributions at https://github.com/NVIDIA/NeMo-Aligner

https://huggingface.co/discussions/paper/66344c29dcf96f82195c53eb