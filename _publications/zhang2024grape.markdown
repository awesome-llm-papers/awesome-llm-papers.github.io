---
layout: publication
title: 'GRAPE: Generalizing Robot Policy Via Preference Alignment'
authors: Zijian Zhang, Kaiyuan Zheng, Zhaorun Chen, Joel Jang, Yi Li, Chaoqi Wang,
  Mingyu Ding, Dieter Fox, Huaxiu Yao
conference: No Venue
year: 2024
bibkey: zhang2024grape
additional_links: [{name: Code, url: 'https://grape-vla.github.io/'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/674e322d6cc0873e3af7d26f'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2411.19309'}]
tags: ["Reinforcement Learning"]
short_authors: Zhang et al.
---
Despite the recent advancements of vision-language-action (VLA) models on a variety of robotics tasks, they suffer from critical issues such as poor generalizability to unseen tasks, due to their reliance on behavior cloning exclusively from successful rollouts. Furthermore, they are typically fine-tuned to replicate demonstrations collected by experts under different settings, thus introducing distribution bias and limiting their adaptability to diverse manipulation objectives, such as efficiency, safety, and task completion. To bridge this gap, we introduce GRAPE: Generalizing Robot Policy via Preference Alignment. Specifically, GRAPE aligns VLAs on a trajectory level and implicitly models reward from both successful and failure trials to boost generalizability to diverse tasks. Moreover, GRAPE breaks down complex manipulation tasks to independent stages and automatically guides preference modeling through customized spatiotemporal constraints with keypoints proposed by a large vision-language model. Notably, these constraints are flexible and can be customized to align the model with varying objectives, such as safety, efficiency, or task success. We evaluate GRAPE across a diverse array of tasks in both real-world and simulated environments. Experimental results demonstrate that GRAPE enhances the performance of state-of-the-art VLA models, increasing success rates on in-domain and unseen manipulation tasks by 51.79% and 60.36%, respectively. Additionally, GRAPE can be aligned with various objectives, such as safety and efficiency, reducing collision rates by 44.31% and rollout step-length by 11.15%, respectively. All code, models, and data are available at https://grape-vla.github.io/

https://huggingface.co/discussions/paper/674e322d6cc0873e3af7d26f