---
layout: publication
title: Can We Generate Images With Cot? Let's Verify And Reinforce Image Generation
  Step By Step
authors: Ziyu Guo, Renrui Zhang, Chengzhuo Tong, Zhizheng Zhao, Peng Gao, Hongsheng
  Li, Pheng-ann Heng
conference: No Venue
year: 2025
bibkey: guo2025can
additional_links: [{name: Code, url: 'https://github.com/ZiyuGuo99/Image-Generation-CoT'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67930410c67af4a116a25da4'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2501.13926'}]
tags: ["Efficiency", "Evaluation", "Has Code", "Prompting", "Reinforcement Learning"]
short_authors: Guo et al.
---
Chain-of-Thought (CoT) reasoning has been extensively explored in large models to tackle complex understanding tasks. However, it still remains an open question whether such strategies can be applied to verifying and reinforcing image generation scenarios. In this paper, we provide the first comprehensive investigation of the potential of CoT reasoning to enhance autoregressive image generation. We focus on three techniques: scaling test-time computation for verification, aligning model preferences with Direct Preference Optimization (DPO), and integrating these techniques for complementary effects. Our results demonstrate that these approaches can be effectively adapted and combined to significantly improve image generation performance. Furthermore, given the pivotal role of reward models in our findings, we propose the Potential Assessment Reward Model (PARM) and PARM++, specialized for autoregressive image generation. PARM adaptively assesses each generation step through a potential assessment approach, merging the strengths of existing reward models, and PARM++ further introduces a reflection mechanism to self-correct the generated unsatisfactory image. Using our investigated reasoning strategies, we enhance a baseline model, Show-o, to achieve superior results, with a significant +24% improvement on the GenEval benchmark, surpassing Stable Diffusion 3 by +15%. We hope our study provides unique insights and paves a new path for integrating CoT reasoning with autoregressive image generation. Code and models are released at https://github.com/ZiyuGuo99/Image-Generation-CoT

https://huggingface.co/discussions/paper/67930410c67af4a116a25da4