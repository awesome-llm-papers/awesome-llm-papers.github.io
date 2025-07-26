---
layout: publication
title: System Prompt Optimization With Meta-learning
authors: Yumin Choi, Jinheon Baek, Sung Ju Hwang
conference: No Venue
year: 2025
bibkey: choi2025system
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.09666'}]
tags: ["Prompting"]
short_authors: Yumin Choi, Jinheon Baek, Sung Ju Hwang
---
Large Language Models (LLMs) have shown remarkable capabilities, with optimizing their input prompts playing a pivotal role in maximizing their performance. However, while LLM prompts consist of both the task-agnostic system prompts and task-specific user prompts, existing work on prompt optimization has focused on user prompts specific to individual queries or tasks, and largely overlooked the system prompt that is, once optimized, applicable across different tasks and domains. Motivated by this, we introduce the novel problem of bilevel system prompt optimization, whose objective is to design system prompts that are robust to diverse user prompts and transferable to unseen tasks. To tackle this problem, we then propose a meta-learning framework, which meta-learns the system prompt by optimizing it over various user prompts across multiple datasets, while simultaneously updating the user prompts in an iterative manner to ensure synergy between them. We conduct experiments on 14 unseen datasets spanning 5 different domains, on which we show that our approach produces system prompts that generalize effectively to diverse user prompts. Also, our findings reveal that the optimized system prompt enables rapid adaptation even to unseen tasks, requiring fewer optimization steps for test-time user prompts while achieving improved performance.

https://huggingface.co/discussions/paper/68269a1eaa8aded616d280d1