---
layout: publication
title: 'Flow-grpo: Training Flow Matching Models Via Online RL'
authors: Jie Liu, Gongye Liu, Jiajun Liang, Yangguang Li, Jiaheng Liu, Xintao Wang,
  Pengfei Wan, di Zhang, Wanli Ouyang
conference: No Venue
year: 2025
bibkey: liu2025flow
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.05470'}]
tags: ["Reinforcement Learning", "Training Techniques"]
short_authors: Liu et al.
---
We propose Flow-GRPO, the first method integrating online reinforcement learning (RL) into flow matching models. Our approach uses two key strategies: (1) an ODE-to-SDE conversion that transforms a deterministic Ordinary Differential Equation (ODE) into an equivalent Stochastic Differential Equation (SDE) that matches the original model's marginal distribution at all timesteps, enabling statistical sampling for RL exploration; and (2) a Denoising Reduction strategy that reduces training denoising steps while retaining the original inference timestep number, significantly improving sampling efficiency without performance degradation. Empirically, Flow-GRPO is effective across multiple text-to-image tasks. For complex compositions, RL-tuned SD3.5 generates nearly perfect object counts, spatial relations, and fine-grained attributes, boosting GenEval accuracy from 63% to 95%. In visual text rendering, its accuracy improves from 59% to 92%, significantly enhancing text generation. Flow-GRPO also achieves substantial gains in human preference alignment. Notably, little to no reward hacking occurred, meaning rewards did not increase at the cost of image quality or diversity, and both remained stable in our experiments.

https://huggingface.co/discussions/paper/681d982aedf34a77aab56635