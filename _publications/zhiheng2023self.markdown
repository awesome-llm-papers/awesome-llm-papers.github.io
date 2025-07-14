---
layout: publication
title: 'Self-polish: Enhance Reasoning In Large Language Models Via Problem Refinement'
authors: Zhiheng Xi, Senjie Jin, Yuhao Zhou, Rui Zheng, Songyang Gao, Tao Gui, Qi
  Zhang, Xuanjing Huang
conference: Arxiv
year: 2023
bibkey: zhiheng2023self
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2305.14497v2'}]
tags: [Evaluation, Datasets, Reinforcement Learning, Prompting, Security]
---
To enhance the multi-step reasoning capabilities of large language models,
researchers have extensively explored prompting methods, notably the
Chain-of-Thought (CoT) method which explicitly elicits human-like rationales.
However, they have inadvertently overlooked the potential of enhancing model
reasoning performance by formulating higher-quality problems. In this work, we
start from the problem side and propose Self-Polish (SP), a novel method that
facilitates the model's reasoning by guiding it to progressively refine the
given problems to be more comprehensible and solvable. We also explore several
automatic prompting varients and propose the Self-Polish prompt bank for the
community. SP is orthogonal to all other prompting methods of answer/reasoning
side like CoT, allowing for seamless integration with state-of-the-art
techniques for further improvement. Thorough experiments show that the proposed
method attains notable and consistent effectiveness on five reasoning
benchmarks across different models. Furthermore, our method also showcases
impressive performance on robustness evaluation. Codes and prompts are
available at https://github.com/WooooDyy/Self-Polish.