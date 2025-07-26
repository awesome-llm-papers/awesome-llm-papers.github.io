---
layout: publication
title: 'OTC: Optimal Tool Calls Via Reinforcement Learning'
authors: Hongru Wang, Cheng Qian, Wanjun Zhong, Xiusi Chen, Jiahao Qiu, Shijue Huang,
  Bowen Jin, Mengdi Wang, Kam-fai Wong, Heng Ji
conference: No Venue
year: 2025
bibkey: wang2025otc
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/68070934142b618d3357d318'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.14870'}]
tags: ["Reinforcement Learning", "Tools"]
short_authors: Wang et al.
---
Tool-integrated reasoning (TIR) augments large language models (LLMs) with the ability to invoke external tools, such as search engines and code interpreters, to solve tasks beyond the capabilities of language-only reasoning. While reinforcement learning (RL) has shown promise in improving TIR by optimizing final answer correctness, existing approaches often overlook the efficiency and cost associated with tool usage. This can lead to suboptimal behavior, including excessive tool calls that increase computational and financial overhead, or insufficient tool use that compromises answer quality. In this work, we propose Optimal Tool Call-controlled Policy Optimization (OTC-PO), a simple yet effective RL-based framework that encourages models to produce accurate answers with minimal tool calls. Our method introduces a tool-integrated reward that jointly considers correctness and tool efficiency, promoting high tool productivity. We instantiate this framework within both Proximal Policy Optimization (PPO) and Group Relative Preference Optimization (GRPO), resulting in OTC-PPO and OTC-GRPO. Experiments with Qwen-2.5 and Qwen-Math across multiple QA benchmarks show that our approach reduces tool calls by up to 73.1% and improves tool productivity by up to 229.4%, while maintaining comparable answer accuracy. To the best of our knowledge, this is the first RL-based framework that explicitly optimizes tool-use efficiency in TIR.

https://huggingface.co/discussions/paper/68070934142b618d3357d318