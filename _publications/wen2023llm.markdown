---
layout: publication
title: 'Autodroid: Llm-powered Task Automation In Android'
authors: Hao Wen et al.
conference: 'ACM MobiCom ''24: 30th Annual International Conference on Mobile Computing
  and Networking'
year: 2023
citations: 21
bibkey: wen2023llm
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.15272'}, {name: Code,
    url: 'https://autodroid-sys.github.io/'}]
tags: [Has Code, Model Architecture, Fine-Tuning, Reinforcement Learning, Efficiency
    and Optimization, GPT, Evaluation]
---
Mobile task automation is an attractive technique that aims to enable
voice-based hands-free user interaction with smartphones. However, existing
approaches suffer from poor scalability due to the limited language
understanding ability and the non-trivial manual efforts required from
developers or end-users. The recent advance of large language models (LLMs) in
language understanding and reasoning inspires us to rethink the problem from a
model-centric perspective, where task preparation, comprehension, and execution
are handled by a unified language model. In this work, we introduce AutoDroid,
a mobile task automation system capable of handling arbitrary tasks on any
Android application without manual efforts. The key insight is to combine the
commonsense knowledge of LLMs and domain-specific knowledge of apps through
automated dynamic analysis. The main components include a functionality-aware
UI representation method that bridges the UI with the LLM, exploration-based
memory injection techniques that augment the app-specific domain knowledge of
LLM, and a multi-granularity query optimization module that reduces the cost of
model inference. We integrate AutoDroid with off-the-shelf LLMs including
online GPT-4/GPT-3.5 and on-device Vicuna, and evaluate its performance on a
new benchmark for memory-augmented Android task automation with 158 common
tasks. The results demonstrated that AutoDroid is able to precisely generate
actions with an accuracy of 90.9%, and complete tasks with a success rate of
71.3%, outperforming the GPT-4-powered baselines by 36.4% and 39.7%. The demo,
benchmark suites, and source code of AutoDroid will be released at
url\{https://autodroid-sys.github.io/\}.