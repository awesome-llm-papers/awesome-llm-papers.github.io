---
layout: publication
title: 'ARM: Adaptive Reasoning Model'
authors: Siye Wu, Jian Xie, Yikai Zhang, Aili Chen, Kai Zhang, Yu Su, Yanghua Xiao
conference: No Venue
year: 2025
bibkey: wu2025arm
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/68352b5903548b71276c1a9f'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.20258'}]
tags: ["Efficiency", "Prompting", "Training Techniques"]
short_authors: Wu et al.
---
While large reasoning models demonstrate strong performance on complex tasks, they lack the ability to adjust reasoning token usage based on task difficulty. This often leads to the "overthinking" problem -- excessive and unnecessary reasoning -- which, although potentially mitigated by human intervention to control the token budget, still fundamentally contradicts the goal of achieving fully autonomous AI. In this work, we propose Adaptive Reasoning Model (ARM), a reasoning model capable of adaptively selecting appropriate reasoning formats based on the task at hand. These formats include three efficient ones -- Direct Answer, Short CoT, and Code -- as well as a more elaborate format, Long CoT. To train ARM, we introduce Ada-GRPO, an adaptation of Group Relative Policy Optimization (GRPO), which addresses the format collapse issue in traditional GRPO. Ada-GRPO enables ARM to achieve high token efficiency, reducing tokens by an average of 30%, and up to 70%, while maintaining performance comparable to the model that relies solely on Long CoT. Furthermore, not only does it improve inference efficiency through reduced token generation, but it also brings a 2x speedup in training. In addition to the default Adaptive Mode, ARM supports two additional reasoning modes: 1) Instruction-Guided Mode, which allows users to explicitly specify the reasoning format via special tokens -- ideal when the appropriate format is known for a batch of tasks. 2) Consensus-Guided Mode, which aggregates the outputs of the three efficient formats and resorts to Long CoT in case of disagreement, prioritizing performance with higher token usage.

https://huggingface.co/discussions/paper/68352b5903548b71276c1a9f