---
layout: publication
title: 'Openagi: When LLM Meets Domain Experts'
authors: Yingqiang Ge, Wenyue Hua, Kai Mei, Jianchao Ji, Juntao Tan, Shuyuan Xu, Zelong
  Li, Yongfeng Zhang
conference: Arxiv
year: 2023
bibkey: ge2023openagi
citations: 63
additional_links: [{name: Code, url: 'https://github.com/agiresearch/OpenAGI'}, {
    name: Paper, url: 'https://arxiv.org/abs/2304.04370'}]
tags: ["Agentic", "Datasets", "Evaluation", "Has Code", "Reinforcement Learning", "Tools"]
short_authors: Ge et al.
---
Human Intelligence (HI) excels at combining basic skills to solve complex
tasks. This capability is vital for Artificial Intelligence (AI) and should be
embedded in comprehensive AI Agents, enabling them to harness expert models for
complex task-solving towards Artificial General Intelligence (AGI). Large
Language Models (LLMs) show promising learning and reasoning abilities, and can
effectively use external models, tools, plugins, or APIs to tackle complex
problems. In this work, we introduce OpenAGI, an open-source AGI research and
development platform designed for solving multi-step, real-world tasks.
Specifically, OpenAGI uses a dual strategy, integrating standard benchmark
tasks for benchmarking and evaluation, and open-ended tasks including more
expandable models, tools, plugins, or APIs for creative problem-solving. Tasks
are presented as natural language queries to the LLM, which then selects and
executes appropriate models. We also propose a Reinforcement Learning from Task
Feedback (RLTF) mechanism that uses task results to improve the LLM's
task-solving ability, which creates a self-improving AI feedback loop. While we
acknowledge that AGI is a broad and multifaceted research challenge with no
singularly defined solution path, the integration of LLMs with domain-specific
expert models, inspired by mirroring the blend of general and specialized
intelligence in humans, offers a promising approach towards AGI. We are
open-sourcing the OpenAGI project's code, dataset, benchmarks, evaluation
methods, and the UI demo to foster community involvement in AGI advancement:
https://github.com/agiresearch/OpenAGI.