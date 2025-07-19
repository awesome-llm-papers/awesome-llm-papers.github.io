---
layout: publication
title: 'AGENTSAFE: Benchmarking The Safety Of Embodied Agents On Hazardous Instructions'
authors: Liu et al.
conference: Risk Analysis
year: 2025
bibkey: liu2025agentsafe
citations: 103
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.14697'}]
tags: [Datasets, Agentic, Tools, Evaluation, Reinforcement Learning, Security, Multimodal
    Models, Responsible AI]
---
The rapid advancement of vision-language models (VLMs) and their integration into embodied agents have unlocked powerful capabilities for decision-making. However, as these systems are increasingly deployed in real-world environments, they face mounting safety concerns, particularly when responding to hazardous instructions. In this work, we propose AGENTSAFE, the first comprehensive benchmark for evaluating the safety of embodied VLM agents under hazardous instructions. AGENTSAFE simulates realistic agent-environment interactions within a simulation sandbox and incorporates a novel adapter module that bridges the gap between high-level VLM outputs and low-level embodied controls. Specifically, it maps recognized visual entities to manipulable objects and translates abstract planning into executable atomic actions in the environment. Building on this, we construct a risk-aware instruction dataset inspired by Asimovs Three Laws of Robotics, including base risky instructions and mutated jailbroken instructions. The benchmark includes 45 adversarial scenarios, 1,350 hazardous tasks, and 8,100 hazardous instructions, enabling systematic testing under adversarial conditions ranging from perception, planning, and action execution stages.