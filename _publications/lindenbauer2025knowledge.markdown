---
layout: publication
title: 'From Knowledge To Noise: Ctim-rover And The Pitfalls Of Episodic Memory In
  Software Engineering Agents'
authors: "Lindenbauer Tobias, Groh Georg, Sch\xFCtze Hinrich"
conference: IEEE Internet Computing
year: 2025
bibkey: lindenbauer2025knowledge
citations: 82
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.23422'}]
tags: [Agentic, Tools, Reinforcement Learning, LLM For Code]
---
We introduce CTIM-Rover, an AI agent for Software Engineering (SE) built on top of AutoCodeRover (Zhang et al., 2024) that extends agentic reasoning frameworks with an episodic memory, more specifically, a general and repository-level Cross-Task-Instance Memory (CTIM). While existing open-source SE agents mostly rely on ReAct (Yao et al., 2023b), Reflexion (Shinn et al., 2023), or Code-Act (Wang et al., 2024), all of these reasoning and planning frameworks inefficiently discard their long-term memory after a single task instance. As repository-level understanding is pivotal for identifying all locations requiring a patch for fixing a bug, we hypothesize that SE is particularly well positioned to benefit from CTIM. For this, we build on the Experiential Learning (EL) approach ExpeL (Zhao et al., 2024), proposing a Mixture-Of-Experts (MoEs) inspired approach to create both a general-purpose and repository-level CTIM. We find that CTIM-Rover does not outperform AutoCodeRover in any configuration and thus conclude that neither ExpeL nor DoT-Bank (Lingam et al., 2024) scale to real-world SE problems. Our analysis indicates noise introduced by distracting CTIM items or exemplar trajectories as the likely source of the performance degradation.