---
layout: publication
title: 'RACER: Rich Language-guided Failure Recovery Policies For Imitation Learning'
authors: Yinpei Dai, Jayjun Lee, Nima Fazeli, Joyce Chai
conference: No Venue
year: 2024
bibkey: dai2024racer
additional_links: [{name: Code, url: 'https://rich-language-failure-recovery.github.io'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/66f227630fa7f61205acaa78'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2409.14674'}]
tags: ["Has Code", "Tools", "Training Techniques"]
short_authors: Dai et al.
---
Developing robust and correctable visuomotor policies for robotic manipulation is challenging due to the lack of self-recovery mechanisms from failures and the limitations of simple language instructions in guiding robot actions. To address these issues, we propose a scalable data generation pipeline that automatically augments expert demonstrations with failure recovery trajectories and fine-grained language annotations for training. We then introduce Rich languAge-guided failure reCovERy (RACER), a supervisor-actor framework, which combines failure recovery data with rich language descriptions to enhance robot control. RACER features a vision-language model (VLM) that acts as an online supervisor, providing detailed language guidance for error correction and task execution, and a language-conditioned visuomotor policy as an actor to predict the next actions. Our experimental results show that RACER outperforms the state-of-the-art Robotic View Transformer (RVT) on RLbench across various evaluation settings, including standard long-horizon tasks, dynamic goal-change tasks and zero-shot unseen tasks, achieving superior performance in both simulated and real world environments. Videos and code are available at: https://rich-language-failure-recovery.github.io.

https://huggingface.co/discussions/paper/66f227630fa7f61205acaa78