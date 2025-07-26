---
layout: publication
title: 'Llm-planner: Few-shot Grounded Planning For Embodied Agents With Large Language
  Models'
authors: Chan Hee Song, Jiaman Wu, Clayton Washington, Brian M. Sadler, Wei-lun Chao,
  Yu Su
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2023
bibkey: song2022llm
citations: 143
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.04088'}]
tags: ["Few-Shot", "ICCV"]
short_authors: Song et al.
---
This study focuses on using large language models (LLMs) as a planner for
embodied agents that can follow natural language instructions to complete
complex tasks in a visually-perceived environment. The high data cost and poor
sample efficiency of existing methods hinders the development of versatile
agents that are capable of many tasks and can learn new tasks quickly. In this
work, we propose a novel method, LLM-Planner, that harnesses the power of large
language models to do few-shot planning for embodied agents. We further propose
a simple but effective way to enhance LLMs with physical grounding to generate
and update plans that are grounded in the current environment. Experiments on
the ALFRED dataset show that our method can achieve very competitive few-shot
performance: Despite using less than 0.5% of paired training data, LLM-Planner
achieves competitive performance with recent baselines that are trained using
the full training data. Existing methods can barely complete any task
successfully under the same few-shot setting. Our work opens the door for
developing versatile and sample-efficient embodied agents that can quickly
learn many tasks. Website: https://dki-lab.github.io/LLM-Planner