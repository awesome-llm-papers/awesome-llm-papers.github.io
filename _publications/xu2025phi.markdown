---
layout: publication
title: 'Phi-4-mini-reasoning: Exploring The Limits Of Small Reasoning Language Models
  In Math'
authors: Haoran Xu, Baolin Peng, Hany Awadalla, Dongdong Chen, Yen-chun Chen, Mei
  Gao, Young Jin Kim, Yunsheng Li, Liliang Ren, Yelong Shen, Shuohang Wang, Weijian
  Xu, Jianfeng Gao, Weizhu Chen
conference: No Venue
year: 2025
bibkey: xu2025phi
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.21233'}]
tags: ["Datasets", "Efficiency", "Fine-Tuning", "Prompting", "Reinforcement Learning", "Training Techniques"]
short_authors: Xu et al.
---
Chain-of-Thought (CoT) significantly enhances formal reasoning capabilities in Large Language Models (LLMs) by training them to explicitly generate intermediate reasoning steps. While LLMs readily benefit from such techniques, improving reasoning in Small Language Models (SLMs) remains challenging due to their limited model capacity. Recent work by Deepseek-R1 demonstrates that distillation from LLM-generated synthetic data can substantially improve the reasoning ability of SLM. However, the detailed modeling recipe is not disclosed. In this work, we present a systematic training recipe for SLMs that consists of four steps: (1) large-scale mid-training on diverse distilled long-CoT data, (2) supervised fine-tuning on high-quality long-CoT data, (3) Rollout DPO leveraging a carefully curated preference dataset, and (4) Reinforcement Learning (RL) with Verifiable Reward. We apply our method on Phi-4-Mini, a compact 3.8B-parameter model. The resulting Phi-4-Mini-Reasoning model exceeds, on math reasoning tasks, much larger reasoning models, e.g., outperforming DeepSeek-R1-Distill-Qwen-7B by 3.2 points and DeepSeek-R1-Distill-Llama-8B by 7.7 points on Math-500. Our results validate that a carefully designed training recipe, with large-scale high-quality CoT data, is effective to unlock strong reasoning capabilities even in resource-constrained small models.

https://huggingface.co/discussions/paper/6812d62be74b39182bd17cdb