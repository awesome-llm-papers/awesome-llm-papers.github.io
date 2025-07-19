---
layout: publication
title: 'Safeagentbench: A Benchmark For Safe Task Planning Of Embodied LLM Agents'
authors: Yin et al.
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2024
bibkey: yin2024safeagentbench
citations: 155
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.13178'}]
tags: [Datasets, ICCV, Alt, Agentic, Tools, Evaluation, Reinforcement Learning, Responsible
    AI]
---
With the integration of large language models (LLMs), embodied agents have
strong capabilities to understand and plan complicated natural language
instructions. However, a foreseeable issue is that those embodied agents can
also flawlessly execute some hazardous tasks, potentially causing damages in
the real world. Existing benchmarks predominantly overlook critical safety
risks, focusing solely on planning performance, while a few evaluate LLMs'
safety awareness only on non-interactive image-text data. To address this gap,
we present SafeAgentBench-the first benchmark for safety-aware task planning of
embodied LLM agents in interactive simulation environments. SafeAgentBench
includes: (1) an executable, diverse, and high-quality dataset of 750 tasks,
rigorously curated to cover 10 potential hazards and 3 task types; (2)
SafeAgentEnv, a universal embodied environment with a low-level controller,
supporting multi-agent execution with 17 high-level actions for 8
state-of-the-art baselines; and (3) reliable evaluation methods from both
execution and semantic perspectives. Experimental results show that, although
agents based on different design frameworks exhibit substantial differences in
task success rates, their overall safety awareness remains weak. The most
safety-conscious baseline achieves only a 10% rejection rate for detailed
hazardous tasks. Moreover, simply replacing the LLM driving the agent does not
lead to notable improvements in safety awareness. More details and code are
available at https://github.com/shengyin1224/SafeAgentBench.