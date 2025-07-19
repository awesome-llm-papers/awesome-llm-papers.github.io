---
layout: publication
title: Self-play Fine-tuning Of Diffusion Models For Text-to-image Generation
authors: Yuan et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: yuan2024self
citations: 1132
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.10210'}]
tags: [Training Techniques, Alt, Prompting, Agentic, CVPR, Evaluation, Reinforcement
    Learning, Fine Tuning, Datasets, Merging]
---
Fine-tuning Diffusion Models remains an underexplored frontier in generative
artificial intelligence (GenAI), especially when compared with the remarkable
progress made in fine-tuning Large Language Models (LLMs). While cutting-edge
diffusion models such as Stable Diffusion (SD) and SDXL rely on supervised
fine-tuning, their performance inevitably plateaus after seeing a certain
volume of data. Recently, reinforcement learning (RL) has been employed to
fine-tune diffusion models with human preference data, but it requires at least
two images ("winner" and "loser" images) for each text prompt. In this paper,
we introduce an innovative technique called self-play fine-tuning for diffusion
models (SPIN-Diffusion), where the diffusion model engages in competition with
its earlier versions, facilitating an iterative self-improvement process. Our
approach offers an alternative to conventional supervised fine-tuning and RL
strategies, significantly improving both model performance and alignment. Our
experiments on the Pick-a-Pic dataset reveal that SPIN-Diffusion outperforms
the existing supervised fine-tuning method in aspects of human preference
alignment and visual appeal right from its first iteration. By the second
iteration, it exceeds the performance of RLHF-based methods across all metrics,
achieving these results with less data.