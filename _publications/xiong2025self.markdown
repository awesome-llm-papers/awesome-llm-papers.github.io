---
layout: publication
title: Self-rewarding Correction For Mathematical Reasoning
authors: Wei Xiong, Hanning Zhang, Chenlu Ye, Lichang Chen, Nan Jiang, Tong Zhang
conference: No Venue
year: 2025
bibkey: xiong2025self
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.19613'}]
tags: ["Reinforcement Learning"]
short_authors: Xiong et al.
---
We study self-rewarding reasoning large language models (LLMs), which can simultaneously generate step-by-step reasoning and evaluate the correctness of their outputs during the inference time-without external feedback. This integrated approach allows a single model to independently guide its reasoning process, offering computational advantages for model deployment. We particularly focus on the representative task of self-correction, where models autonomously detect errors in their responses, revise outputs, and decide when to terminate iterative refinement loops. To enable this, we propose a two-staged algorithmic framework for constructing self-rewarding reasoning models using only self-generated data. In the first stage, we employ sequential rejection sampling to synthesize long chain-of-thought trajectories that incorporate both self-rewarding and self-correction mechanisms. Fine-tuning models on these curated data allows them to learn the patterns of self-rewarding and self-correction. In the second stage, we further enhance the models' ability to assess response accuracy and refine outputs through reinforcement learning with rule-based signals. Experiments with Llama-3 and Qwen-2.5 demonstrate that our approach surpasses intrinsic self-correction capabilities and achieves performance comparable to systems that rely on external reward models.

https://huggingface.co/discussions/paper/67c12989505a88e4a185e115