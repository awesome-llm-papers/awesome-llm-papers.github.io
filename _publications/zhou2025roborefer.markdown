---
layout: publication
title: 'Roborefer: Towards Spatial Referring With Reasoning In Vision-language Models
  For Robotics'
authors: Enshen Zhou, Jingkun An, Cheng Chi, Yi Han, Shanyu Rong, Chi Zhang, Pengwei
  Wang, Zhongyuan Wang, Tiejun Huang, Lu Sheng, Shanghang Zhang
conference: No Venue
year: 2025
bibkey: zhou2025roborefer
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/68424dc88d0422fce0273fb5'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.04308'}]
tags: ["Datasets", "Evaluation", "Fine-Tuning", "Reinforcement Learning", "Training Techniques"]
short_authors: Zhou et al.
---
Spatial referring is a fundamental capability of embodied robots to interact with the 3D physical world. However, even with the powerful pretrained vision language models (VLMs), recent approaches are still not qualified to accurately understand the complex 3D scenes and dynamically reason about the instruction-indicated locations for interaction. To this end, we propose RoboRefer, a 3D-aware VLM that can first achieve precise spatial understanding by integrating a disentangled but dedicated depth encoder via supervised fine-tuning (SFT). Moreover, RoboRefer advances generalized multi-step spatial reasoning via reinforcement fine-tuning (RFT), with metric-sensitive process reward functions tailored for spatial referring tasks. To support SFT and RFT training, we introduce RefSpatial, a large-scale dataset of 20M QA pairs (2x prior), covering 31 spatial relations (vs. 15 prior) and supporting complex reasoning processes (up to 5 steps). In addition, we introduce RefSpatial-Bench, a challenging benchmark filling the gap in evaluating spatial referring with multi-step reasoning. Experiments show that SFT-trained RoboRefer achieves state-of-the-art spatial understanding, with an average success rate of 89.6%. RFT-trained RoboRefer further outperforms all other baselines by a large margin, even surpassing Gemini-2.5-Pro by 17.4% in average accuracy on RefSpatial-Bench. Notably, RoboRefer can be integrated with various control policies to execute long-horizon, dynamic tasks across diverse robots (e,g., UR5, G1 humanoid) in cluttered real-world scenes.

https://huggingface.co/discussions/paper/68424dc88d0422fce0273fb5