---
layout: publication
title: Improve Mathematical Reasoning In Language Models By Automated Process Supervision
authors: Liangchen Luo, Yinxiao Liu, Rosanne Liu, Samrat Phatale, Harsh Lara, Yunxuan
  Li, Lei Shu, Yun Zhu, Lei Meng, Jiao Sun, Abhinav Rastogi
conference: No Venue
year: 2024
bibkey: luo2024improve
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6669064773d2031011583c9a'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2406.06592'}]
tags: ["Efficiency", "Evaluation", "Prompting", "Reinforcement Learning"]
short_authors: Luo et al.
---
Complex multi-step reasoning tasks, such as solving mathematical problems or generating code, remain a significant hurdle for even the most advanced large language models (LLMs). Verifying LLM outputs with an Outcome Reward Model (ORM) is a standard inference-time technique aimed at enhancing the reasoning performance of LLMs. However, this still proves insufficient for reasoning tasks with a lengthy or multi-hop reasoning chain, where the intermediate outcomes are neither properly rewarded nor penalized. Process supervision addresses this limitation by assigning intermediate rewards during the reasoning process. To date, the methods used to collect process supervision data have relied on either human annotation or per-step Monte Carlo estimation, both prohibitively expensive to scale, thus hindering the broad application of this technique. In response to this challenge, we propose a novel divide-and-conquer style Monte Carlo Tree Search (MCTS) algorithm named OmegaPRM for the efficient collection of high-quality process supervision data. This algorithm swiftly identifies the first error in the Chain of Thought (CoT) with binary search and balances the positive and negative examples, thereby ensuring both efficiency and quality. As a result, we are able to collect over 1.5 million process supervision annotations to train a Process Reward Model (PRM). Utilizing this fully automated process supervision alongside the weighted self-consistency algorithm, we have enhanced the instruction tuned Gemini Pro model's math reasoning performance, achieving a 69.4% success rate on the MATH benchmark, a 36% relative improvement from the 51% base model performance. Additionally, the entire process operates without any human intervention, making our method both financially and computationally cost-effective compared to existing methods.

https://huggingface.co/discussions/paper/6669064773d2031011583c9a